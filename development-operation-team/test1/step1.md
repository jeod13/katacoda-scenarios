# Copy the repository 
execute the following command to clone the repository
`git clone https://github.com/jeod13/wordpress`{{copy}}

# Start the docker stack
run the following command
`cd wordpress`{{copy}}
`docker-compose up`{{copy}}


# Add datasource to mysql wordpress database
tap the + next to the terminal and open a new terminal

To connect to the MySQL Server, use the docker exec -it command to start a bash 
shell. 
`docker exec -it wordpress_db_1 bash`{{copy}}

Start the mysql client inside the container you have started
`mysql -u root -p`{{copy}}
Use the password somewordpress to login

Select the wordpress database
`use wordpress`{{copy}}

add the datasource into wordpress database
`source comp3335groupprojectsql.sql`{{copy}}

to show the updated database
`show databases;`{{copy}}

# Start setup wordpress
tap the + next to the terminal and select port to view on Host1-->Enter port 8080

Setup wordpress
	Site Title: a
	Username: WordPressTesting
	Password: Wo@rd_Press!Testing
	email: a@a.com

