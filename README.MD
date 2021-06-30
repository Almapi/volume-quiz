# Do you know what is happening here on the host with the directory structure?
## Can you answer this questions before you execute docker-compose build and docker-compose up?
 1. Does the ```docker-compose build``` command creates directories on host machine?
 2. Does the ```docker-compose up``` command creates directories on host machine?
 3. How many folders are created on your **host** machine?
 4. How many folders do you have in your running docker container?
 5. Which directory permissions do you have on a Linux system?
 6. Create a file on **host** ./core folder! Answer true or false if files exists on host
 7. Does ./foo/core on **host** have a file?
 8. Does ./bar/core on **host** have a file?
 9. Now, go into the container! 
 10. Does /app/foo/core inside the docker container have a file?
 11. docker exec -it ${CONTAINERID} ls -la /app/foo/core
 12. Does /app/bar/core inside the docker container have a file?
 13. docker exec -it ${CONTAINERID} ls -la /app/bar/core

 14. Delete the test file on **host** in the directory ./core, now!
 15. Create a new file on host in the directory ./foo/core
 16. Is the file on host in ./core ?
 17. Is the file on host in ./bar/core ? 
 18. Can you find the file inside the docker container somewhere?
