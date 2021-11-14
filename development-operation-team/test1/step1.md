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
`WP Force SSL & HTTPS Redirect`{{copy}}<br />

4. click install Now
5. In the left sidebar click plugin and activate the installed plugin

6. Enable HTTP Strict Transport Security (HSTS)

7. Save Change
8. click the Test site's SSL certificate to test<br />
Sample result:<br />

# Effect of the plugin
Your website is more secure, all the traffic will be encryted using SSL. <br />
And it will enforce user to access your website using HTTPS to prevent user to use a unencryted connection.<br />
So it will maintain the privacy and integrity of customer data.


