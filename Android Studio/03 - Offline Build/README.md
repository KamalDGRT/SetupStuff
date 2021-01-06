# Offline Build for Gradle and Google Maven Depndencies

Sometimes what happens is that your internet connection might be unstable or might not be there 
at all. So, to build applications even though the internet is down, you need to have all the files 
required to build it offline. 

<br>

Even though you have a good internet connection, the build process might take a lot of time. So,
in order to make the development faster, just download all the offline components. 

<br>

<hr>

### Step 1 - Downloading the Offline Files

Go to the download section of the offical Android website from [here](https://developer.android.com/studio).

![Downloads](img/01.png)

<br>

Click on *DOWNLOAD OPTIONS*.

![Downloads](img/02.png)

<br>

Click on _Android Gradle Plugin_.<br>

You will be seeing something like this.<br>

![Downloads](img/03.png)

<br>

Accept the terms and conditions.<br>
Then click on the _DOWNLOAD OFFLINE COMPONENTS FOR ANDROID GRADLE PLUGIN_ button. <br>
A file with the name _offline-android-gradle-plugin-preview.zip_ will get downloaded. <br>

<br>

Click on _Google Maven dependencies_.<br>

You will be seeing something like this.<br>

![Downloads](img/04.png)

<br>

Accept the terms and conditions. <br>
Then click on the _DOWNLOAD OFFLINE COMPONENTS FOR GOOGLE MAVEN DEPENDENCIES_ button. <br>
A file with the name _offline-gmaven-stable.zip_ will get downloaded. <br>

<br>

Based on your internet connection, it would take some time to download. 

<br>

![Downloads](img/05.png)

<hr>

### Step 2 - Placing the downloaded files in proper folders

#### Step 2.1

Open Command Prompt and type the following. <br>

        set USER_HOME

If you get a file path, then it is well and good. <br>
If not, type the following. <br>

        set USERPROFILE

![CMD](img/06.png)

<br>

Now, copy the file path and open it in the File Explorer. <br>
So, I will be opening this location in my File Explorer. <br>

        C:\Users\user

![CMD](img/07.png)

<br>

#### Step 2.2

Inside the above mentioned path, there will be many folders.  <br>
But the ones we are concerned about now are *.gradle* and *.android* . <br>

Now, copy the _offline-android-gradle-plugin-preview.zip_ to *.android* folder. <br>
Right click on that .zip file and select _Extract Here_. <br>

![CMD](img/08.png)

<br>

Now, a folder will present itslef in *.android* folder. <br>

For me it is *android-gradle-plugin-3.5.0-beta01*. <br>
For you it may or may not be the same. <br>
It all depends on when you are installing it. <br>

![folder](img/09.png)

<br>

Now, rename that folder to *manual-offline-m2* . <br>

So, in my case, I will be renaming *android-gradle-plugin-3.5.0-beta01* to *manual-offline-m2*.

<br>

![folder](img/10.png)

<br>

If you still have any doubts as to how the folder is arranged, click [here](dot_android.md) to see the directory structure of *.android* folder. <br>

<br>

You may now delete the _offline-android-gradle-plugin-preview.zip_ file from _.android_ folder. 

<br>

##### To update the offline components, proceed as follows: 

<br>

1. Delete the content inside the manual-offline-m2/ directory. <br>
2. Re-download the offline components. <br>
3. Unzip the contents of the ZIP files you downloaded into the manual-offline-m2/ directory.

<br>

<hr>

### Step 3 - Include offline components in your Gradle project

To tell the Android build system to use the offline components you've downloaded and unzipped, you need to create a script, as described below. Keep in mind, you need to create and save this script only once, even after updating your offline components. <br>

#### Step 3.1

Go to *.gradle* folder. <br>
Create a folder with the name *init.d*. <br>
Inside that folder, create this file : _offline.gradle_ <br>


#### Step 3.2

Open that with any text editor of your choice and paste the following script inside of it. <br>

```
def reposDir = new File(System.properties['user.home'], ".android/manual-offline-m2")
def repos = new ArrayList()
reposDir.eachDir {repos.add(it) }
repos.sort()

allprojects {
  buildscript {
    repositories {
      for (repo in repos) {
        maven {
          name = "injected_offline_${repo.name}"
          url = repo.toURI().toURL()
        }
      }
    }
  }
  repositories {
    for (repo in repos) {
      maven {
        name = "injected_offline_${repo.name}"
        url = repo.toURI().toURL()
      }
    }
  }
}
```

#### Step 3.3

Save the _offline.gradle_ file.

#### Step 3.4 (Totally Optional)

If you’d like to verify that the offline components are working as intended, remove the online repositories from your project’s `build.gradle` files, as shown below. After you've confirmed that your project builds correctly without these repositories, you can put them back into your `build.gradle` files.
