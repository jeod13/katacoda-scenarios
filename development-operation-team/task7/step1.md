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
`Woocommerce`{{copy}}<br />
4. click install Now<br />
5. In the left sidebar click plugin and activate the plugin that you have installed<br />

# Download plugin for wordpress
1. In the left sidebar click plugin
2. click the Add New next to the Plugins on the top left side of the page
3. Search plugins with the following keyword<br />
`User Role Editor`{{copy}}<br />
4. click install Now<br />
5. In the left sidebar click plugin and activate the plugin that you have installed<br />

# Step to Create user with different role(privileges)
1. Create the new roles in User Role Editor (Account -> User Role Editor) and set the Role name and display name in User Role Editor page.<br />
2. Change the "Select Role and change its capabilities" to "Front(Front) " in User Role Editor page.<br />
3. After than use Role changed to Front(Front) , you need to select the roles for this group such as Activate plugins, Create posts, Delete others pages….<br /><br />

For example, sales team only need to upload/update/delete the product in WooCommerce. You can just Shop manager role which allow them to manage the product in WooCommerce without using other function in wordpress. <br /><br />

4. When you set up a new role, you can see the role in the Add New User page (Users -> Add New) can select the role just created(Front).<br />
5. You can see the user list (Users -> All Users) to see all the user’s role and you can edit their information to change their role in Users page.<br />

# Purpose of this scenario
This scenario aims to teach you how to give appropriate privilege to different staff. Not too much privilege and Not too less privilege for them to do their work. Enforcing least privilege is a best practice that is instrumental in reducing security risk and minimizing business disruption that may result from errors or malicious intent. For example, if there is too much privilege to sales team, he/she may misconfigure the website setting and cause your website not available. This scenario is response to the weak authorization problem in company.
