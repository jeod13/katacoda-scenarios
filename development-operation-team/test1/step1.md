# Copy the repository 
execute the following command to clone the repository<br />
`git clone https://github.com/jeod13/wordpress`{{copy}}

# Start the docker stack
run the following command<br />
`cd wordpress`{{copy}}
`docker-compose up`{{copy}}


# Add datasource to mysql wordpress database
tap the + next to the terminal and open a new terminal<br />

To connect to the MySQL Server, use the docker exec -it command to start a bash 
shell. <br />
`docker exec -it wordpress_db_1 bash`{{copy}}

Start the mysql client inside the container you have started<br />
`mysql -u root -p`{{copy}}<br />
Use the password somewordpress to login

Select the wordpress database<br />
`use wordpress`{{copy}}

add the datasource into wordpress database<br />
`source comp3335groupprojectsql.sql`{{copy}}

to show the updated database<br />
`show databases;`{{copy}}

# Start setup wordpress
tap the + next to the terminal and select port to view on Host1-->Enter port 8080

Setup wordpress<br />
	Site Title: a<br />
	Username: `WordPressTesting`{{copy}}<br />
	Password: `Wo@rd_Press!Testing`{{copy}}<br />
	email: a@a.com<br />
	
# Download plugin for wordpress
