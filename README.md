# GUI-based-login-system-with-email-verification-in-java
The objective of this project is self-explanatory. It is a login system that is created using java(swings, JDBC, SMTP).

You will need :

(for sending email)
mail.jar
activation.jar

(for connecting to the database)
mysql-connector-java-8.0.16.jar

PROJECT DEMO :


Login Page : 


![image](https://user-images.githubusercontent.com/71375735/126866746-a81a5f9d-0414-4c6d-9bca-c7b3b3c94599.png)

To create this project GUI based i have used JFrame . And for connecting to the database i have used JDBC.And for sending mail to the user for verification i have used smtp.

There are total 5 frames.
1)Login
2)signup
3)forgot password
4)guest
5)home page

First of all when user runs the program Login frame will open from there he will have 4 options 1)Login 2)signup 3)guest 4)forgot password
as shown in above image.

if user enters his/her username and password and presses Login button than authentication process will take place and if authentication is successful than user will be redirected to home page and if authentication fails than an error message will show up as shown below.
if login is successful 

![image](https://user-images.githubusercontent.com/71375735/126867058-1d5a0c83-bbfd-4f00-9eb3-29c4553be50e.png)

if login failed 


![image](https://user-images.githubusercontent.com/71375735/126867023-04e15a07-aaf5-4015-a808-97be6d4568fb.png)


if user does not have an account and want to create one than he could press on signup button than signup frame will show up.

![image](https://user-images.githubusercontent.com/71375735/126867115-6047701e-3a33-4d57-9606-a84d3c280fa7.png)


Here user can enter his/her details.
if email address is wrong than one dialogbox will show up as shown in image.

![image](https://user-images.githubusercontent.com/71375735/126867193-2301e4e1-dfed-420e-8608-accda5396b2f.png)


If user tries to signup with username which already exist than below dialogbox will showup.


![image](https://user-images.githubusercontent.com/71375735/126867307-9cb64ece-af4a-44ae-9701-8019a8ae4985.png)


or tries to create account from same email address again than below dialogbox will showup.


![image](https://user-images.githubusercontent.com/71375735/126867344-cb2b0d27-8a25-428c-ab53-d009d05be22e.png)


if signup is successful than one verification code will be sent to users email address as shown below.


![image](https://user-images.githubusercontent.com/71375735/126867624-6857ae67-61ff-4788-9170-6eeea32fd4ea.png)


Email will look like this


![image](https://user-images.githubusercontent.com/71375735/126867646-e3081dff-0721-4d8c-a248-1e7b4466fc34.png)


Than user will have to enter the code if the code is correct than user will be redirected to homepage and one column for that user will be added if code is wrong than below message will show up.


![image](https://user-images.githubusercontent.com/71375735/126867672-e6f6e4af-5f43-43b1-9c84-1a595413a0c5.png)


if successful than


![image](https://user-images.githubusercontent.com/71375735/126867683-1ba391f7-d84e-4763-b589-7a8bed345a9c.png)


Now, if user doesn't have an account and doesn't want to create one either than he could press guest button which will show him/her below frame.


![image](https://user-images.githubusercontent.com/71375735/126867747-96408577-358e-4390-844f-ed2f86b47923.png)


than user can enter the username which they like and they will be redirected to homepage *BUT "_guest" will be added after their username* as shown below.


![image](https://user-images.githubusercontent.com/71375735/126867805-42a8d3a8-c1f5-4348-9a8d-c8ababbf1f9f.png)


If user have an account but forgot the password than they can use forgot password option.


![image](https://user-images.githubusercontent.com/71375735/126867849-15ea528a-bb9a-4d69-94b6-e48cc67b11c0.png)


thier they can enter thier previous username and New password as shown below.


![image](https://user-images.githubusercontent.com/71375735/126867890-4966f14b-00c5-4cf1-9230-515e3d0e56da.png)


After that an email will be sent to user .(Email address will be the one which they used for signing up)


![image](https://user-images.githubusercontent.com/71375735/126867956-093a62b2-3996-4393-92f7-8d60b0cc1903.png)


if the user entered code is true than he/she will be redirected to homepage


![image](https://user-images.githubusercontent.com/71375735/126867991-667a3768-7232-4431-b4a5-2cdc985f9e02.png)


and email address , username , password will be stored in database.


![image](https://user-images.githubusercontent.com/71375735/126868012-b3952d0d-01a7-493f-a472-dbd159b8be47.png)


That's all from my side if anyone wants to ask anything about this project than feel free to contact me.

my email address is : ajaydeepsangbhai@gmail.com


Thank you.






