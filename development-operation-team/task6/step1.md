# Copy the repository 
execute the following command to clone the repository<br />
`git clone https://github.com/jeod13/wordpress`{{execute}}

# Start the docker stack
run the following command<br />
`cd wordpress`{{execute}}<br />
`docker-compose up`{{execute}}

# Start setup wordpress
tap the + next to the terminal and select port to view on Host1-->Enter port 8080

1. select language<br /><br />
2. Fill in the following information<br />
Site Title: a<br />
Username: `WordPressTesting`{{copy}}<br />
Password: `Wo@rd_Press!Testing`{{copy}}<br />
email: a@a.com<br /><br />
3. Login with the created account
	
# Download plugin for wordpress
1. In the left sidebar click plugin
2. click the Add New next to the Plugins on the top left side of the page
3. Search plugins with the following keyword<br />
`miniOrange 2-Factor`{{copy}}<br />
4. click install Now<br />
5. In the left sidebar click plugin and activate the plugin that you have installed<br />


# Step to set 2-factor authentication
1. miniorange--> two-factor authentication<br />
2. choose GoogleAuthenticator<br />
3. Click reconfigure<br />

# Step to use 2-factor authentication
1. Download your authenticator app e.g. google authenticator<br />
2. Scan QR Code that shown on the screen to add this account <br />
3. Enter the code from your authenticator app to verify and activate two-factor authentication for this account.<br />

# To test the 2-factor authentication
1. logout the wordpress and login with your wordpress account again<br />
2. there will be a prompt to ask the one time passcode, Enter the one time passcode shown in the Authenticator app.<br />
3. Login Success<br />

# Benefit of 2-factor authentication

It strengthen the existing of password-based authentication by Having a second form of identification which greatly decreases the chance of a hacker gaining access to corporate devices or other sensitive information.
