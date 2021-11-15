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
`WP Activity Log`{{copy}}<br />
4. click install Now<br />
5. In the left sidebar click plugin and activate the plugin that you have installed<br />

# step to use the plugin
You can see the all activity logs in Activity Log Viewer page(WP Activity Log -> Log Viewer).<br />

# The benefit of centralizede logging
Centralized logging group all the log records in a single location, greatly simplifying log analysis and correlation tasks.
It will show all the activity that happen in Wordpress and Woocommerce. For example, someone login, check out, access resources etc. For some abnormal activity suchas login failed many times in Wordpress and Woocommerce,it will notify you for further action to be taken.
