
Assignment-1
--------------------------
1. Use official shell script to install and configure Docker on your control machine.

![image](images/1.png)

2. Start Docker service and check status of the same.

![image](images/2.png)

3. Enable Docker service to start at every machine reboot.

![image](images/3.png)

4. Display Docker version.

![image](images/4.png)

5. Configure non root user to run docker commands without sudo.

![image](images/5.png)

6. Type docker on commandline and read output i.e containing related commands.

![image](images/6.png)

7. Display System information using Docker.

![image](images/7.png)

8. Check whether you can access/download images from DockerHub or not.

![image](images/8.png)

Assignment-2
--------------------------

1. Run a docker container from "hello-world" image.

![image](images/9.png)

2. Pull "alpine" image from docker registry and see if image is available in your local image list.

![image](images/10.png)

3. Pull some specific version of docker "alpine" image from docker registry.

![image](images/11.png)

4. Run a docker container from local image "alpine" and run an inline command "ls -l" while running container.

![image](images/12.png)

5. Try to take login to container created using "alpine" image.

![image](images/13.png)

6. Detach yourself from the container without making it exit/container kill.

![image](images/14.png)

7. Check running containers and see if you can find out the stopped containers.

![image](images/15.png)

8. Stop running container.

![image](images/16.png)

9. Start container that was stopped earlier.

![image](images/17.png)

10. Try to remove "alpine" image from your local system.

![image](images/18.png)

Assignment-3
--------------------------

1. Again pull "alpine" image from docker registry.

![image](images/19.png)

2. Take interactive login to bash while running docker container from "alpine" image.

![image](images/20.png)

3. Run command inside container:
4. echo "hello world" > hello.txt
5. ls

![image](images/21.png)

6. Take exit from same container without killing the container.

![image](images/22.png)

7. Run another container using below command and check if you can find hello.txt within this container. You should find container isolations from step 3-5.

![image](images/23.png)

8. docker container run alpine ls

![image](images/24.png)

9. Stop a container using Container ID.

![image](images/25.png)

10. Start same container using ID and exec a command "echo 'hello world!'" in docker container without instantiating a new container.

![image](images/26.png)

11. Inspect already downloaded "alpine" docker image using docker inspect command.

![image](images/27.png)

12. Tag your local "alpine" image with name "myimage" along with version 1.0

![image](images/28.png)
