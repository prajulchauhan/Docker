## Topic: Docker Installation on Centos 7

Topics to be Covered
-------------------------
* Installing Docker using yum or apt.
* Installing Docker Automatically using official shell script.
* Docker Architecture
* Docker Engine
* Docker Daemon
* Docker Client

What You Will Learn
----------------------------
How easy it is to install and configure Docker for yourself.
How docker client communicated with Docker daemon.


Assignment-1
--------------------------
1. Use official shell script to install and configure Docker on your control machine.



![image](image/1.png)



2. Start Docker service and check status of the same.



![image](image/2.png)



3. Enable Docker service to start at every machine reboot.



![image](image/3.png)



4. Display Docker version.




![image](image/4.png)




5. Configure non root user to run docker commands without sudo.




![image](image/5.png)




6. Type docker on commandline and read output i.e containing related commands.




![image](image/6.png)




7. Display System information using Docker.



![image](image/7.png)



8. Check whether you can access/download images from DockerHub or not.



![image](image/8.png)


Assignment-2
--------------------------

1. Run a docker container from "hello-world" image.



![image](image/9.png)



2. Pull "alpine" image from docker registry and see if image is available in your local image list.



![image](image/10.png)




3. Pull some specific version of docker "alpine" image from docker registry.



![image](image/11.png)



4. Run a docker container from local image "alpine" and run an inline command "ls -l" while running container.




![image](image/12.png)




5. Try to take login to container created using "alpine" image.




![image](image/13.png)




6. Detach yourself from the container without making it exit/container kill.



![image](image/14.png)




7. Check running containers and see if you can find out the stopped containers.





![image](image/15.png)



8. Stop running container.




![image](image/16.png)




9. Start container that was stopped earlier.



![image](image/17.png)




10. Try to remove "alpine" image from your local system.



![image](image/18.png)



Assignment-3
--------------------------

1. Again pull "alpine" image from docker registry.



![image](image/19.png)



2. Take interactive login to bash while running docker container from "alpine" image.



![image](image/20.png)




3. Run command inside container:
4. echo "hello world" > hello.txt
5. ls



![image](image/21.png)



6. Take exit from same container without killing the container.



![image](image/22.png)



7. Run another container using below command and check if you can find hello.txt within this container. You should find container isolations from step 3-5.
8. docker container run alpine ls



![image](image/23.png)


9. Stop a container using Container ID.




![image](image/24.png)



10. Start same container using ID and exec a command "echo 'hello world!'" in docker container without instantiating a new container.




![image](image/25.png)




11. Inspect already downloaded "alpine" docker image using docker inspect command.



![image](image/26.png)



12. Tag your local "alpine" image with name "myimage" along with version 1.0



![image](image/27.png)




Reference
----------------
[Docker Installation](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-centos-7)

[Docker Cli](https://docs.docker.com/engine/reference/run/) 
