# Docker Hands-On Lab Questions

This repository contains Docker hands-on lab **questions/tasks** divided into three sections according to the PDF files.

---

## 🟢 docker_1 Tasks (Task 1 to 18)

1. Docker Installation – Install Docker and verify installation.  
2. Working with Docker Images – Search, pull, and list Docker images.  
3. Creating a Docker Container – Run Ubuntu container and execute a command.  
4. Inspect Container (Created State) – Verify container state.  
5. Run Container (Running State) – Start container and check running state.  
6. Launch and Remove HTTP Container – Launch HTTP container, verify, and remove container & image.  
7. List Short Container IDs – Display only short container IDs.  
8. Clone & Build Custom Image – Clone `lancachenet/ubuntu-nginx` repo and build Docker image with tags.  
9. Run & Test the Webpage – Run container from custom image and verify webpage with `curl`.  
10. Container Detach & Reattach – Launch container, detach, reattach, check IP.  
11. Inspect Host Configuration – Inspect hostname and `/etc/hosts` of httpd container.  
12. Monitor Container Stats – Check container stats using `top` command.  
13. Nginx Containers Log Review – Compare logs of Nginx containers.  
14. System Events & Filters – Filter Docker system events by date, time, name, and event.  
15. Custom Hostname & Logs – Create container with custom hostname, stop/kill, check exit code & logs.  
16. Container Management Operations – Pause, unpause, stop, start, restart, inspect stats & events, rename containers.  
17. DockerHub Repository Setup – Create DockerHub account and repository.  
18. Complete Docker tasks by EOD – Run all above tasks by deadline.  

---

## 🔵 Docker_2 Tasks (Task 19 to 36)

19. Run four HTTPD containers with distinct restart policies (NO, On-Failure, Always, Unless-Stopped).  
20. Change restart policy of a running container using `docker update`.  
21. Launch NGINX container with custom `index.html` on host port 80.  
22. Run Docker container with CPU and memory limits.  
23. Update CPU and memory of Docker container using `docker update`.  
24. Pull Busy-box image, tag it, and push to DockerHub.  
25. Create Dockerfile with NGINX and custom HTML, build, push, map port 8080.  
26. Push Redis images (version 1 and 3) to DockerHub.  
27. Create Git repo, build image from release branch, run container on host port 8383, push to DockerHub, merge pull request.  
28. Save local Redis images as `.tar`, delete local images, push repo, load images from tar.  
29. Pull Busy-box, export NGINX container image as `.tar`, import, tag, push to DockerHub.  
30. Create simple Dockerfile (Ubuntu + curl, vim, git + environment variable).  
31. Create directories `DHUB` and `AWSECR`.  
32. Create Dockerfiles for DHUB and AWSECR with HTTPD, index.html content, env variables, expose port 80.  
33. Build custom images and list available images.  
34. Push images to DockerHub and AWS ECR.  
35. Run containers: DHUB (8081) and AWSECR (8082).  
36. Access pages from browser to verify content.  

---

## 🟣 docker_3 Tasks (Task 37 to 50)

37. Create Dockerfile (Ubuntu + curl, vim, git + environment variable).  
38. Docker networking – Two containers on same custom network, verify communication.  
39. Data persistence with volumes – Create file in volume, verify after container removal.  
40. Docker Compose – Multi-container app with web & database, same network.  
41. Container logging – Generate logs, analyze with `docker logs`.  
42. Container resource monitoring – Monitor CPU/memory usage with `docker stats` & `docker top`.  
43. Update containerized application – Rebuild image & deploy updated version.  
44. Bridge network – Connect two containers (NGINX & MySQL) using user-defined bridge network.  
45. Port mapping – Run web server and map default port to custom host port.  
46. Host networking – Run container with host networking, compare configuration.  
47. Named volume – Launch DB container, remove & recreate using same volume, verify data persists.  
48. Bind mount – Web app with local directory mounted in container, verify updates reflect.  
49. Volume backups – Backup named volume data, restore to new container, verify.  
50. Docker Compose networking – Multi-container app (frontend, backend, database) with custom networks & volumes, verify communication & persistence.  

---
