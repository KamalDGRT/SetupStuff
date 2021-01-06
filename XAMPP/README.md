# Setup Instructions for XAMPP


## For Windows PC


The instructions here is for a Windows PC. <br>
For Linux and Mac, it will be added later.


It would be better and preferrable if you install in a specific folder rather than the default path of
C:\xampp. 

<br>

### Step 1
Download the Xampp application from here : https://www.apachefriends.org/index.html <br>
The download size is around 150MB. 

<br>

<hr>

### Step 2

Create a folder in C drive and name it anything you want. <br>
It is preferred if the maximum length of the folder is 8 characters.<br>
For example, I am going to name it LEO.<br>

So, in C drive, there is a folder with the name LEO.<br>
       
       C:\LEO

<br>


<hr>

### Step 3


Click on the downloaded application.<br>
        
![UAC](img/01.png)

 <br>
You might see a warning like this. This was why I told you to create the folder. <br>
By creating our own folder, we need not worry about the permissions mentioned in that warning box.<br>
Now, click OK.<br><br>


<hr>

### Step 4

Click Next.<br>

![UAC](img/02.png)

<br>

<hr>

### Step 5

Just leave all the stuff as it is and let us install everything that XAMPP can provide. <br>

![UAC](img/03.png)


<hr>

### Step 6

By default, it would be <br>

        C:\xampp
        
  Change it to  <br>
  
        C:\LEO\xampp
   
  ![UAC](img/04.png)
<br>

<hr>

### Step 7

If you want leave as it is, it is your choice.<br>
But, I don't want to know more about Bitnami.<br>
So, I am just unselecting it.<br>
Click Next.<br>

![UAC](img/05.png)

<br>

<hr>

### Step 8

Now, click Next.<br>
The installation will go on for 5 to 10 minutes depending on your system specifications. <br>

![UAC](img/06.png)

<br><br>

<hr>

### Step 9

Click Finish.<br>

![UAC](img/07.png)

<br>

<hr>

### Step 10

Select English.<br>

![UAC](img/08.png)

<br>

<hr>

### Step 11

And now the Control Panel is ready.

![UAC](img/09.png)

<br>

We will be mostly using the _Apache_ and _MySQL_ server.

<br>

<hr>

### Step 12

Start the Apache and MySQL servers.<br>
You might get some message boxes like these.<br>

![UAC](img/10.png)

<br>

![UAC](img/11.png)

<br>

Just click _Allow Acess_.

Now, the _Apache_ and _MySQL_ servers are up and running.

![UAC](img/12.png)
<br>

<hr>

### Step 13

Click on Admin of _Apache_ server. <br>
If all went fine, you should be seeing something like this: <br>

![UAC](img/13.png)

<br>

<hr>

### Step 14

Click on Admin of _MySQL_ server. <br>
You will something like this: <br>

![UAC](img/14.png)

<br>

<hr>

### Note :

If one or both the servers didn't start, it might be because the same port might be used by some other application like VMWare or any other SQL servers. <br>
Based on experience, my advice would be not to tamper with the existing XAMPP config files. <br>
So, change the port number of the other applications. <br>
