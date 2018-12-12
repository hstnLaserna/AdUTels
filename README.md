# Hotel Booking Website

	Members:
	 1.	Laserna, Justine Ildefonso
	 2.	Mbonyingabo Karuta, Christian
	 3.	Mukamugemanyi, Jolie Josiane
	 4.	Reomales, Cedric Joel Remolacio


## Installation Instructions

	1.   Clone the repository using the following command ```git clone https://github.com/hstnLaserna/AdUTels.git```
	2.   Go the cloned folder and create the images by running ```docker build --file .docker/Dockerfile -t laravel-docker .```
	3.   Run the containers using ```docker-compose up -d --build```.
	3.   Initialize the backend tables by going to the link based on your available docker machine:
			For Native Docker installation: ```localhost\database\mysqli.php```
			For Docker toolbox installation: ```192.168.99.100\database\mysqli.php```
	4.   Visit the website still based on your available docker machine:
			For Native Docker installation:```localhost```
			For Docker toolbox installation: ```192.168.99.100```

		
Please be minded that the database may not initialize on some machines due to "account restriction".
We don't have the same 'root' accounts so you might need to change the following from the files:
		/Database/conn.php
			Line 4: $user = "root";
			Line 5: $pass = "root"; (or what password you use)
		/Database/mysqli.php
			Line 7: $username = "root";
			Line 8: $password = "root"; (or what password you use)
			
## This website will be able to:
		-Sign up(for new users)
		-Login(existing users) & Logout
		-Book a hotel room 
		-View booked rooms 
		-Update a hotel room 
		-Delete a hotel room 
		-change the user's account password