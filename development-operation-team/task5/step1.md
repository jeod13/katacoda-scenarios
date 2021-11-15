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
`WooCommerce`{{copy}}<br />

4. click install Now<br />
5. In the left sidebar click plugin and activate the plugin that you have installed<br />

# Update the plugin
method 1: simply enable auto-update<br />
In the left sidebar click plugin and select the plugin and click enable auto-update<br /><br />

method 2: update manually<br />
if you worry about the compatibility with other plugins, <br />
you can try to install the latest plugin in your local environment to test the compatibility with other plugins.<br /><br />
After you confirmed all thins work together well, you can backup the website and try to patch your website.<br />

# Remember to backup all the data before update any plugin
<br /><br />
# Benefit of update the plugin

A plugin update may include new features, fix issurs, improve security. <br /><br />
you are recommended to keep all of the plugins in their latest version.<br /><br />
For example, Woocommerce discover that Woocommerce plugin is vulnerable to a critical SQL injection vulnerability in July 2021. And Woocommerce update a patch to fix the problem.<br />

If you do not update the plugin frequently,it may suffer from security problem. And the customer/user's personal data that store on Wordpress may hacked by hacker which reduce the confidentiality of user's personal data.<br /><br />
So, You are highly recommended to update the plugin once there is a latest version
