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
`BackWPup`{{copy}}<br />

4. click install Now<br />
5. In the left sidebar click plugin and activate the plugin that you have installed<br />

# Create a Backup task
click BackWPup that show in the left sidebar of the wordpress --> Add new job<br /><br />
In general tab <br />
you can tick different option to select the task to be include. <br />
For example database backup, file backup, wordpress XML export, installed plugins list and check database tables.<br />

you can also backup to different destination for example backup to folder,dropbox, S3,FTP or sent to email etc.<br /><br />


In schedule Tab<br />
you can setup a schedular to backup the wordpress and database in an specific time automatically.<br /><br />

In DB backup tab<br />
you can select which table to be backup.<br /><br />

Remember to click save change button on the bottom left of the page<br />

click BackWPup that show in the left sidebar of the wordpress-->Jobs-->run the job you have created<br />

click BackWPup that show in the left sidebar of the wordpress-->Backup--->Download<br />
 
# (Recommended) encryted the backup using BakcWPup pro
BackWPup Pro → Settings and then select the Encryption tab<br />

select the asymmetric method, BackWPup generates an RSA key pair. <br /><br />
Both keys will be offered to you for download. <br /><br />
download the private key at least. Next, click Use these keys<br /><br />

tick Encrypt Archive when you created/ammend you task to encrypt backup during creation<br />

# Benefit of backup with encrytion
it support encryted the backup file using asymmetrical procedure which uses the RSA algorithm and the AES procedure. <br /><br />
It store data in a safer environment as only you own the private RSA key which can maintain the integrity and confidentiality of data.<br /><br />
It also responce to the GDPR requirement to protect backup that include customer/user's private data. <br /><br />
Once there is a data leak exist, it is still difficult for hacker/someone to extract the sensitive data. <br /><br />
