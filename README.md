# AgileProject
Complete practical commands (for your lab exam)
Run these commands in the same order:
# 1. Check Docker version
docker --version

# 2. Pull Ubuntu image
docker pull ubuntu

# 3. List downloaded images
docker images

# 4. Create and run container
docker run -it --name myubuntu ubuntu

# 5. Inside Ubuntu container
ls
cat /etc/os-release

# 6. Exit container
exit

# 7. List all containers
docker ps -a

# 8. Inspect container
docker inspect myubuntu

# 9. Start container
docker start myubuntu

# 10. Stop container
docker stop myubuntu

# 11. Remove container
docker rm myubuntu

# 12. Verify container removal
docker ps -a

# 13. Verify image still exists
docker images


Practical result
Experiment completed
We successfully demonstrated Docker image and container management by:
1. Pulling the Ubuntu image from Docker Hub.
2. Listing downloaded Docker images.
3. Creating and running an Ubuntu container.
4. Inspecting container details.
5. Listing running and stopped containers.
6. Starting and stopping the container.
7. Removing the container.
8. Verifying that the image still exists.
Conclusion: Thus, we successfully performed Docker image and container management using Docker commands.

Important viva questions with answers
Q1. What is Docker?

Answer: Docker is a platform used to develop, package and run applications inside containers.

Q2. What is a Docker image?

Answer: A Docker image is a read-only template used to create containers.

Q3. What is a Docker container?

Answer: A container is a running instance of a Docker image.

Q4. What is Docker Hub?

Answer: Docker Hub is an online platform used to store and share Docker images.

Q5. Which command pulls an image?

Answer: docker pull ubuntu

Q6. Which command lists images?

Answer: docker images

Q7. Which command lists running containers?

Answer: docker ps

Q8. Which command lists all containers?

Answer: docker ps -a

Q9. Which command inspects a container?

Answer: docker inspect myubuntu

Q10. Which command stops a container?

Answer: docker stop myubuntu

Q11. Which command removes a container?

Answer: docker rm myubuntu

Q12. What is the difference between docker stop and docker rm?

Answer:
- docker stop stops a running container.
- docker rm removes a stopped container.
Q13. Does removing a container delete its image?

Answer: No. The image remains available until we remove it separately.

Q14. What is the difference between Docker image and container?

Answer: An image is a template, whereas a container is an instance created from that image.

Q15. What does -it mean?

Answer: -i keeps input open and -t allocates a terminal.

Exam tip: Remember these five important commands:
docker pull ubuntu
docker images
docker run -it --name myubuntu ubuntu
docker inspect myubuntu
docker stop myubuntu
docker rm myubuntu


These commands cover the main operations your practical examiner is likely to ask you to demonstrate.
