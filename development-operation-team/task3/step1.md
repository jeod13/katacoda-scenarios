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
`GDPR Cookie Consent & Compliance Notice`{{copy}}<br />

4. click install Now<br />
5. In the left sidebar click plugin and activate the plugin that you have installed<br />

# Create Cookie list
From the left sidebar go to GDPR Cookie Consent --> Cookie List<br /><br />

you can click the add cookie to create a new cookie.<br />
You can specify the title, description, cookie Category, Cookie type, cookie duration, cookie sensitivity etc of the cookie that you created.<br />

# Show cookie group by category
From the left sidebar go to GDPR Cookie Consent --> Cookie category<br /><br />

It show all the cookies in your website based on category <br />
such as Advertisement cookies, Analytics cookies, Functional cookies, Necessary cookies etc<br />

# generate policy of cookie.
From the left sidebar go to GDPR Cookie Consent --> Policy generator<br /><br />

you can add new policy to explain how you will use the cookie, type of cookie is used etc.<br />

# generate a privacy overview
From the left sidebar go to GDPR Cookie Consent --> Privacy overview<br /><br />

you can create a privacy overview to show the purpose of the cookies when user access the webpage.<br /> 
So users may decide whether they accepted the cookies based on the privacy overview.<br /> 

# Purpose of this scenario
To fulfill The General Data Protection Regulation (GDPR) requirement, website should ask for and obtain the clear and affirmative consents from users before processing any of their data.<br /> <br />  This scenario aims to teach the way to ask for consent using plugin in WordPress and teach developers need to clearly state the ways they use the user’s data. 
