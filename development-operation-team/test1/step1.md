# Copy the repository 
execute the following command to clone the repository<br />
`git clone https://github.com/jeod13/wordpress`{{execute}}

# Start the docker stack
run the following command<br />
`cd wordpress`{{execute}}
`docker-compose up`{{execute}}


# Add datasource to mysql wordpress database
tap the + next to the terminal and open a new terminal<br />

To connect to the MySQL Server, use the docker exec -it command to start a bash 
shell. <br />
`docker exec -it wordpress_db_1 bash`{{execute}}

Start the mysql client inside the container you have started<br />
`mysql -u root -p`{{execute}}<br />
Use the password `somewordpress`{{execute}} to login

Select the wordpress database<br />
`use wordpress`{{execute}}

add the datasource into wordpress database<br />
`source comp3335groupprojectsql.sql`{{execute}}

to show the updated database<br />
`show databases;`{{execute}}

# Start setup wordpress
tap the + next to the terminal and select port to view on Host1-->Enter port 8080

Setup wordpress<br />
	Site Title: a<br />
	Username: `WordPressTesting`{{copy}}<br />
	Password: `Wo@rd_Press!Testing`{{copy}}<br />
	email: a@a.com<br />
	
# Download plugin for wordpress
