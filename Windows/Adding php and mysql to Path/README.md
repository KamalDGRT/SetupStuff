  # Adding php and mysql to the path variable

This step is done after installtion of XAMPP.<br>
In case you have not intalled XAMPP, click [here](https://github.com/KamalDGRT/SetupStuff/tree/master/XAMPP) for the installation steps.<br>

### Step 1

Open Start Menu and type `edit the system environment variables`.<br>
You will get something like this. <br>
Just click and open it.

![Start Menu](https://github.com/KamalDGRT/static/blob/master/SetupStuf/php_mysql/img/01.png)

<br>

<hr>

### Step 2

You might get something like this : <br>

![Image](https://github.com/KamalDGRT/static/blob/master/SetupStuf/php_mysql/img/02.png)

Just click on _Evnvironment Variables..._

<br>

<hr>

### Step 3

Do you have _Path_ variable in the variables? <br>

#### Yes, I have _Path_ in the user variables

_Click_ on _Path_ and _Click_ on _Edit.._ <br>
Click _New_. <br>
Add this line.<br>

      C:\LEO\xampp\php

Like I told you before, I will be using the _LEO_ folder.<br>
Plus, this is where I installed the _XAMPP_.<br>
So, if you have installed it in a different folder, just change the path accordingly.<br>

Click _New.._ Again.<br>
Add this line.<br>

      C:\LEO\xampp\mysql\bin

<br>
After that, Click _OK_.<br>
Click _OK_ again.<br>
Click _OK_ once again.<br>

#### No, I do not have _Path_ in the user variables

##### Step 3.1

So, if you do not have _Path_ in the user variables then the environmental variables menu must be something like this. <br>

![Env](https://github.com/KamalDGRT/static/blob/master/SetupStuf/php_mysql/img/03.png)

<br>

Click on _New..._

<br>

<hr>

##### Step 3.2

In the variable name, type _Path_. <br>

![Env](https://github.com/KamalDGRT/static/blob/master/SetupStuf/php_mysql/img/04.png)

<br>

In the variable value, add this line. <br>

      C:\LEO\xampp\php
      
![Env](https://github.com/KamalDGRT/static/blob/master/SetupStuf/php_mysql/img/05.png)

Click OK.

<br>

<hr>

##### Step 3.3

Click on _Path_. <br>

![Env](https://github.com/KamalDGRT/static/blob/master/SetupStuf/php_mysql/img/06.png)<br>

Click on _Edit.._.<br>

![Env](https://github.com/KamalDGRT/static/blob/master/SetupStuf/php_mysql/img/07.png) <br>

And in the variable value, add this line.<br>

      C:\LEO\xampp\php; C:\LEO\xampp\mysql\bin;

![Env](https://github.com/KamalDGRT/static/blob/master/SetupStuf/php_mysql/img/08.png)

<br>
If you have done it correctly, the next time you click edit, it should be like this : <br>

![Env](https://github.com/KamalDGRT/static/blob/master/SetupStuf/php_mysql/img/09.png)

<br>

Click OK.

<br>

![Env](https://github.com/KamalDGRT/static/blob/master/SetupStuf/php_mysql/img/10.png)

Click OK.

![Env](https://github.com/KamalDGRT/static/blob/master/SetupStuf/php_mysql/img/11.png)

<br>

<hr>

### Step 4

To check if you have added the paths correctly, just open the command prompt and execute the following commands.<br>

      php --version
      
<br>

      mysql --version

![Env](https://github.com/KamalDGRT/static/blob/master/SetupStuf/php_mysql/img/12.png)

<hr>
