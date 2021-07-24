# GUI-based-login-system-with-email-verification-in-java
The objective of this project is self-explanatory. It is a login system that is created using java(swings, JDBC, SMTP).

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

if login is successful: ![image](https://user-images.githubusercontent.com/71375735/126867058-1d5a0c83-bbfd-4f00-9eb3-29c4553be50e.png)



if login failed : ![image](https://user-images.githubusercontent.com/71375735/126867023-04e15a07-aaf5-4015-a808-97be6d4568fb.png)


if user does not have an account and want to create one than he could press on signup button than signup frame will show up.
![image](https://user-images.githubusercontent.com/71375735/126867115-6047701e-3a33-4d57-9606-a84d3c280fa7.png)


Here user can enter his/her details.
if email address is wrong than one dialogbox will show up as shown in image.
![image](https://user-images.githubusercontent.com/71375735/126867193-2301e4e1-dfed-420e-8608-accda5396b2f.png)



