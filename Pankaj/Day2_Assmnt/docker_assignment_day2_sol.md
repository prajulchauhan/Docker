Assignment 1

Docker Port:

Pull nginx image from dockerhub.

![image](images/1.png)

Run a container from nginx image and map container port 80 to system port 80.

![image](images/2.png)

Display all mapped ports on nginx image.

![image](images/3.png)

Run a docker container named "containexpose" from nginx image and expose port 80 of container to outer world without mapping it to any of system port.

![image](images/4.png)

Docker Volume:

Create docker volume named "dbvol"

![image](images/5.png)

Run docker container from wordpress image and mount "dbvol" to /var/lib/mysql

![image](images/6.png)

Display all docker volumes.

![image](images/7.png)

Create another docker volume named "testvol"

![image](images/8.png)

Remove docker volume "testvol"

![image](images/9.png)

Docker Linking:

Run a container in detached mode with name "db" from image "training/postgres"

![image](images/10.png)

Run another container in detached mode with name "web" from image "training/webapp", link container "db" with alias "mydb" to this container and finally pass an inline command "python app.py" while running container.

![image](images/11.png)

Take a bash terminal in "web" container.

![image](images/12.png)

Test container linking by doing a ping to "mydb"

![image](images/13.png)