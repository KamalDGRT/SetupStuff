# Flutter Installation in Windows


#### Note :

If you have : <br>
 - gone somewhere and installed it before
 - installed *Dart* separately
 
 uninstall it and remove all the files. <br>

<br>

## Step 1 - Pre-requisites

> Before proceeding with *Flutter* installation, make sure you have done the following list. <br>
> I am saying this because, I have installed it in this way and this has worked for me. <br>

- [x] Installed [Git](../Git/README.md)
- [x] Installed [GitHub Desktop](../GitHub_Desktop/README.md) *(Optional)*
- [x] Proper installation and setting up of [Android Studio](https://github.com/KamalDGRT/SetupStuff/tree/master/Android%20Studio)
- [x] Installed [Microsoft Visual Studio Code](https://github.com/KamalDGRT/SetupStuff/blob/master/Microsoft%20Visual%20Studio%20Code/README.md) *(Optional but highly recommended)*

<br>

<hr>

<br>

## Step2 - Go to *Installation Folder* 

Like I have mentioned in the [README](https://github.com/KamalDGRT/SetupStuff/blob/master/README.md) of this repository, I will be installing *Flutter* in the *LEO* folder and I suggest you to do it in the same way. <br>

Go to the *LEO* folder in the *File Explorer*.<br>
Open *Command Prompt* at that folder location by typing *cmd* and pressing *Enter* in the **Address Bar** of *LEO* folder.<br>
Type out this following command to get the **stable** version of the *Flutter SDK* in that folder. <br>

        git clone https://github.com/flutter/flutter.git -b stable


You will be seeing something like this : 

<br>

![Flutter](img/01.png)

<br>

The *flutter* folder would look something like this :

![Flutter](img/02.png)

<br>

<hr>

<br>

## Step3 - Adding Flutter to the *Path* variable

### Step 3.1

Open Start Menu and type `edit the system environment variables`.<br>
You will get something like this. <br>
Just click and open it.

![Start Menu](img/03.png)

<br>

<hr>

### Step 3.2

You might get something like this : <br>

![Image](img/04.png)

Just click on _Evnvironment Variables..._

<br>

<hr>

### Step 3.3 

_Click_ on _Path_ and _Click_ on _Edit.._ <br>

![Image](img/05.png)


Click _New_. <br>

![Image](img/06.png)

Add this line.<br>

      C:\LEO\flutter\bin

![Image](img/07.png)

After that, Click _OK_.<br>

Click _OK_ again.

<br>

![Image](img/08.png)

<br>

Click _OK_ once again.<br>

![Image](img/09.png)

<br>

<hr>

<br>

## Step4 - Fetching the Dart SDK

Open the *Command Prompt*. <br>

Type the following commands to check if *Java* and *Kotlin* exist in your Path Variable: 

      java --version

<br>

      kotlinc -version

<br>

      kotlin -version

<br>

Now run the *flutter doctor* command to get the Dart SDK. <br>

      flutter doctor

<br>

![Image](img/10.png)

<br>

Now, this will fetch the Dart SDK to your PC and place it somewhere inside *flutter* folder. <br>

![Image](img/11.png)

<br>

![Image](img/12.png)

<br>

When it's all done, you will be greeted with a screen like this:

![Image](img/13.png)

<br>

<hr>

## Step5 - Accpeting the Android Licences

In the above image you can see that some weren't checked. Now, let's fix them all. <br>
First, let's fix the Android licenses checkbox.<br>
<br>

Run this command on the *Command Prompt*. <br>

      flutter doctor --android-licenses

<br>

After you run this command, there will be lots of description and it will prompt you to press 'y' to accept those Terms and Conditions.  So, just go ahead and accept them all.

<hr>

## Step6 - Flutter and Dart Plugin in Android Studio

The next checkbox to be fixed is the Flutter and Dart plugin in Android Studio. <br>

### Step 6.1 

Open **Android Studio** and select ***Plugins*** which is there on the bottom-right corner. <br>
Click on *Plugins*. <br>


![Image](img/14.png)

<br>

### Step 6.2 : Installing Dart Plugin

Search *Dart* in the *Marketplace* tab. <br>
Install the plugin by *JetBrains* by clicking on *Install*.

![Image](img/15.png)

<br>

It might ask for some persmmion to install. Just accept them. <br>
It might also ask you to Restart the IDE and I recommend you to do the same. 

<br>

### Step 6.3 : Installing Flutter Plugin

Open **Android Studio** and select ***Plugins*** which is there on the bottom-right corner. <br>
Click on *Plugins*. <br>


![Image](img/14.png)

<br>

Search *Flutter* in the *Marketplace* tab. <br>
Install the plugin by *flutter.dev* by clicking on *Install*.

![Image](img/16.png)

<br>

It might ask for some persmmion to install. Just accept them. <br>

![Image](img/17.png)


It might ask you to Restart the IDE and I recommend you to do the same. 

![Image](img/18.png)

<br>

![Image](img/19.png)

<br>

### Step 6.4 : Checking if everthing went fine

Run the following command in *Command Prompt* to check the version of Flutter. <br>

      flutter --version

<br>
Now, run the following command to check if everything is fine with flutter. <br>

      flutter doctor

<br>

Now, except for the devices part, everything should be checked. Like this :

![Image](img/20.png)


<br>

<hr>

## Step7 - Adding Dart to path variable (Optional but recommended)

After installing Flutter, you might want to use the Dart for normal coding purposes instead of just using it while building apps. So, for that, you will have to add Dart to the *Path* variable.

### Step 7.1

Open Start Menu and type `edit the system environment variables`.<br>
You will get something like this. <br>
Just click and open it.

![Start Menu](img/21.png)

<br>

<hr>

### Step 7.2

You might get something like this : <br>

![Image](img/22.png)

Just click on _Evnvironment Variables..._

<br>

<hr>

### Step 7.3 

_Click_ on _Path_ and _Click_ on _Edit.._ <br>

![Image](img/23.png)


Click _New_. <br>

![Image](img/24.png)

Add this line.<br>

      C:\LEO\flutter\bin\cache\dart-sdk\bin


Note: The path might vary based on where you've installed flutter. So, change it accordingly.

![Image](img/25.png)

After that, Click _OK_.<br>

Click _OK_ again.

<br>

![Image](img/26.png)

<br>

Click _OK_ once again.<br>

![Image](img/27.png)

<br>

<hr>

<br>


## Step8 - Setting up devices for executing the apps

There are 2 ways to setup devices for flutter.<br><br>

You can use the built-in AVD Manager in Android Studio. <br>
But when you do that, your CPU might be using a lot of RAM and might get heated up quickly.<br>
Again, it all depends on your system configuration and specification. <br><br>


Another way to add a device for flutter is to use an actual Android or iOS device.<br>
For Android devices, enable USB debugging in your device settings. <br>
If there's no such option, then you must enable the Developer Tools by clicking on the build tools 7 times. <br>
After that enable USB debugging and allow apps to be installed using ADB.<br>
When you connect your device after you enable these settings, it might show like allow this device to access your phone in your mobile device. <br>
Just click yes.<br><br>

-And this is it, you may now go and start building *Flutter* applications.

