## Topic: Docker PORT/VOLUME/LINK

Topics to be Covered
------------------------
* Working with Docker port forwarding.
* Attaching docker volume to a container.
* Link containers.

Assignment 1
-------------------
## Docker Port:
1. Pull nginx image from dockerhub.



![image](image/1.png)



2. Run a container from nginx image and map container port 80 to system port 80.



![image](image/2.png)



3. Display all mapped ports on nginx image.



![image](image/3.png)



4. Run a docker container named "containexpose" from nginx image and expose port 80 of container to outer world without mapping it to any of system port.



![image](image/14.png)



## Docker Volume:


1. Create docker volume named "dbvol"



![image](image/5.png)



2. Run docker container from wordpress image and mount "dbvol" to /var/lib/mysql




![image](image/6.png)



![image](image/7.png)


3. Display all docker volumes.




![image](image/8.png)




4. Create another docker volume named "testvol"



![image](image/9.png)


5. Remove docker volume "testvol"



![image](image/10.png)




## Docker Linking:

1. Run a container in detached mode with name "db" from image "training/postgres"



![image](image/11.png)



2. Run another container in detached mode with name "web" from image "training/webapp", link container "db" with alias "mydb" to this container and finally pass an inline command "python app.py" while running container.



![image](image/12.png)



3. Take a bash terminal in "web" container.
4. Test container linking by doing a ping to "mydb"


![image](image/13.png)




Reference
-----------------
[Docker Port/Volume/Link](https://docs.docker.com/engine/reference/commandline/run/)
