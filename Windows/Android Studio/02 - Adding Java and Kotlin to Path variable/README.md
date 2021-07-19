# Creating Necessary Path Variables

### Step 1

Open Start Menu and type `edit the system environment variables`.<br>
You will get something like this. <br>
Just click and open it.

![Start Menu](https://github.com/KamalDGRT/static/blob/master/SetupStuf/anstudio/java_kotlin/img/01.png)

<br>

<hr>

### Step 2

You might get something like this : <br>

![Image](https://github.com/KamalDGRT/static/blob/master/SetupStuf/anstudio/java_kotlin/img/02.png)

Just click on _Evnvironment Variables..._

<br>

<hr>

### Step 3 - Adding ANDROID_HOME variable

Under the `User variables` click `New....`.

![Paths](https://github.com/KamalDGRT/static/blob/master/SetupStuf/anstudio/java_kotlin/img/03.png)

It will show something like this:

![Paths](https://github.com/KamalDGRT/static/blob/master/SetupStuf/anstudio/java_kotlin/img/04.png)

For the variable name, give `ANDROID_HOME`. <br>

![Paths](https://github.com/KamalDGRT/static/blob/master/SetupStuf/anstudio/java_kotlin/img/05.png)

For the variable value, give the path to the `Android SDK` which in our case is : <br> 

```
C:\LEO\Android\SDK
```

![Paths](https://github.com/KamalDGRT/static/blob/master/SetupStuf/anstudio/java_kotlin/img/06.png)

<br>

Click `OK`.

<hr>

### Step 4 - Adding JAVA_HOME variable

Under the `User variables` click `New....`.

![Paths](https://github.com/KamalDGRT/static/blob/master/SetupStuf/anstudio/java_kotlin/img/07.png)

For the variable name, give `JAVA_HOME`. <br>
For the variable value, give the path to `Java Runtime Environment` ; which in our case is : <br>

```
C:\LEO\Android\Android Studio\jre
```

![Paths](https://github.com/KamalDGRT/static/blob/master/SetupStuf/anstudio/java_kotlin/img/08.png)

<br>

Click `OK`.

<hr>

### Step 5 - Adding Java, Kotlin and some stuff to the Path variable

_Click_ on _Path_ and _Click_ on _Edit.._ <br>

![Paths](https://github.com/KamalDGRT/static/blob/master/SetupStuf/anstudio/java_kotlin/img/09.png)

Click _New_. <br>

![Paths](https://github.com/KamalDGRT/static/blob/master/SetupStuf/anstudio/java_kotlin/img/10.png)

Add this line.<br>

```
C:\LEO\Android\Android Studio\jre\bin
```

![Paths](https://github.com/KamalDGRT/static/blob/master/SetupStuf/anstudio/java_kotlin/img/11.png)

Click _New.._ Again.<br>
Add this line.<br>

```
C:\LEO\Android\SDK\platform-tools
```

![Paths](https://github.com/KamalDGRT/static/blob/master/SetupStuf/anstudio/java_kotlin/img/12.png)

Click _New.._ Again.<br>
Add this line.<br>

```
C:\LEO\Android\SDK\tools
```

Click _New.._ Again.<br>
Add this line.<br>

```
C:\LEO\Android\Android Studio\plugins\Kotlin\kotlinc\bin
```

![Paths](https://github.com/KamalDGRT/static/blob/master/SetupStuf/anstudio/java_kotlin/img/13.png)

<br>

Click `OK`.

<br>

![Env](https://github.com/KamalDGRT/static/blob/master/SetupStuf/anstudio/java_kotlin/img/14.png)

Click `OK`.

![Env](https://github.com/KamalDGRT/static/blob/master/SetupStuf/anstudio/java_kotlin/img/15.png)

<hr>

This is it. Now you have configured all the path variables for setting up app development using Java and Kotlin. <br>
We added Java and Kotlin to the `Path` variable because, we may want to learn, code and execute `Java` and `Kotlin` programs separately. At that time, these configurations will come handy!
