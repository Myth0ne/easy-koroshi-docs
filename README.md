## Pre requisites
node.js is required for this tool on the machine you are running this on. For more info go here to install - https://nodejs.org/en/download 

## Install instructions
1.	Navigate to https://www.thekoroshi.com/realm
2.	Press F12 or right click page -> Inspect
3.	Change to Network tab
4.	Note: You may need to refresh the page for this. You need to find the getMyNfts result


 ![image](https://github.com/user-attachments/assets/67ae1903-bef2-4eb1-9bc3-7efe76520afc)

6.	Retrieve the cookie from Request Header section. You just need the first section where it says connect.sid and copy the string until the first semi-colon like below.


 ![image](https://github.com/user-attachments/assets/8c2ce8c9-28b5-4b68-b855-f8dd7b1dfc94)


8.	Go to your machine whether you do this locally or ssh into another remote device on your network.
10.	Copy or download the files here - https://github.com/0xMesiya/easy-koroshi
11.	Navigate to the directory in a terminal of your choice
12.	Run ```npm install```
13.	create a file called “.env” in the text editor of your choice
14.	paste the cookie string you got from step 5 into the .env file, save .env file. The file should look like this ```CONNECT_SID='xxxxx'```
17.	run the tool by running the command ```node main.js```
