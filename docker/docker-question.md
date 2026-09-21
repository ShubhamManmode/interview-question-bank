# Docker Interview Questions

## 1. Docker Fundamentals

1. What is Docker?
2. Why do we use Docker?
3. What problem does Docker solve?
4. What is a container?
5. What is a Docker image?
6. What is the difference between a Docker image and a Docker container?
7. What is the difference between a Docker container and a Virtual Machine?
8. What is Docker Engine?
9. What is Docker Hub?
10. What is a Docker Registry?
11. What is Azure Container Registry (ACR)?
12. What is the difference between Docker Hub and ACR?

---

## 2. Dockerfile

13. What is a Dockerfile?
14. What is the purpose of the `FROM` instruction?
15. What is the purpose of `WORKDIR`?
16. What is the difference between `COPY` and `ADD`?
17. What is the purpose of `RUN`?
18. What is the purpose of `EXPOSE`?
19. What is the purpose of `ENV`?
20. What is the difference between `CMD` and `ENTRYPOINT`?
21. What is the purpose of `.dockerignore`?
22. How do you create a Dockerfile for a .NET 8 application?
23. What is a multi-stage Docker build?
24. Why are multi-stage builds used?
25. How can you reduce Docker image size?
26. What is a base image?
27. What is the difference between SDK and Runtime images in .NET?
28. Why should we use the .NET runtime image in the final Docker image?

---

## 3. Docker Commands

29. How do you build a Docker image?
30. How do you run a Docker container?
31. How do you list running containers?
32. How do you list all containers?
33. How do you stop a container?
34. How do you start a stopped container?
35. How do you restart a container?
36. How do you remove a container?
37. How do you remove a Docker image?
38. How do you view container logs?
39. How do you enter a running container?
40. How do you inspect a container?
41. How do you inspect a Docker image?
42. How do you view Docker images?
43. How do you check Docker container resource usage?
44. What is the difference between `docker run` and `docker start`?
45. What is the difference between `docker exec` and `docker attach`?

---

## 4. Docker Networking

46. How does Docker networking work?
47. What is a Docker network?
48. What is the default Docker bridge network?
49. What is a custom bridge network?
50. How do two Docker containers communicate with each other?
51. How do you create a Docker network?
52. How do you connect a container to a Docker network?
53. What is port mapping in Docker?
54. What does `-p 8080:80` mean?
55. What is the difference between `EXPOSE` and `-p`?
56. Can two containers communicate without exposing their ports to the host?
57. What does `localhost` mean inside a Docker container?
58. How does one microservice communicate with another microservice running in Docker?
59. What is Docker DNS?
60. How does Docker resolve container names?

---

## 5. Docker Volumes and Storage

61. What happens to data when a Docker container is deleted?
62. What is a Docker volume?
63. Why do we need Docker volumes?
64. What is a bind mount?
65. What is the difference between a volume and a bind mount?
66. How do you create a Docker volume?
67. How do you mount a volume to a container?
68. How would you persist SQL Server data running inside Docker?
69. Should databases store their production data inside the container filesystem? Why?

---

## 6. Environment Variables and Configuration

70. How do you pass environment variables to a Docker container?
71. How do you pass configuration to an ASP.NET Core application running inside Docker?
72. How does ASP.NET Core read environment variables?
73. How do you handle Development, Staging, and Production configurations?
74. Should secrets be stored inside a Dockerfile?
75. How do you securely provide database connection strings to containers?
76. How would you integrate Docker with Azure Key Vault?

---

## 7. Docker Compose

77. What is Docker Compose?
78. Why do we use Docker Compose?
79. What is a `docker-compose.yml` file?
80. How do you run multiple containers using Docker Compose?
81. How do containers communicate with each other in Docker Compose?
82. What is `depends_on`?
83. What are Docker Compose services?
84. How do you expose ports using Docker Compose?
85. How do you configure environment variables in Docker Compose?
86. How do you configure volumes in Docker Compose?
87. How do you create a .NET API + Redis + SQL Server setup using Docker Compose?
88. What is the difference between Docker Compose and Kubernetes?

---

## 8. Docker and .NET

89. How do you containerize a .NET 8 application?
90. How do you build a Docker image for an ASP.NET Core API?
91. What should the Dockerfile for a .NET 8 application contain?
92. Why do we use the .NET SDK image during the build stage?
93. Why do we use the ASP.NET runtime image in the final stage?
94. How do you expose an ASP.NET Core API from a Docker container?
95. How do you configure ASP.NET Core ports inside Docker?
96. How do you pass an ASP.NET Core connection string to Docker?
97. How do you run database migrations when deploying a .NET application in Docker?
98. How do you debug a .NET application running inside a Docker container?

---

## 9. Docker Security

99. How do you secure Docker containers?
100. Why should applications not run as root inside containers?
101. What is a non-root Docker user?
102. How do you scan Docker images for vulnerabilities?
103. How do you protect secrets in Docker?
104. Why should passwords not be hardcoded in a Dockerfile?
105. What is a minimal/base image?
106. What are Docker image vulnerabilities?
107. How can you reduce the attack surface of a Docker image?

---

## 10. Docker Troubleshooting

108. A container starts and immediately stops. How do you troubleshoot it?
109. What is `docker logs` and how do you use it?
110. How do you troubleshoot a container in `Exited` state?
111. How do you troubleshoot a container that keeps restarting?
112. What is a Docker healthcheck?
113. How do you troubleshoot a failed health check?
114. The application works locally but doesn’t work inside Docker. What would you check?
115. The container cannot connect to SQL Server. How would you troubleshoot it?
116. The container cannot connect to Redis. How would you troubleshoot it?
117. The API is running inside Docker but cannot be accessed from the browser. What would you check?
118. Why does `localhost` sometimes cause problems when applications communicate inside Docker?
119. What is `CrashLoopBackOff` in Kubernetes and how is it related to container failures?
120. What is `ImagePullBackOff` and how would you troubleshoot it?

---

## 11. Docker Performance

121. How do you reduce Docker image size?
122. How do you improve Docker build performance?
123. What is Docker layer caching?
124. Why is Docker layer caching useful?
125. How does the order of instructions in a Dockerfile affect build performance?
126. How do you optimize a .NET Docker image?
127. How do you monitor Docker container CPU and memory usage?
128. What happens when a container exceeds its memory limit?

---

## 12. Docker with Microservices

129. How would you containerize multiple .NET microservices?
130. How do multiple microservices communicate using Docker?
131. How would you run multiple .NET microservices locally?
132. How would you configure service-to-service communication?
133. How would you handle configuration for multiple microservices?
134. How would you handle secrets across microservices?
135. How would you implement logging for multiple containers?
136. How would you monitor multiple containers?
137. How would you handle service discovery?
138. How would you implement load balancing between multiple containers?

---

## 13. Docker + Azure

139. How do you push a Docker image to Azure Container Registry?
140. How does AKS pull images from ACR?
141. How do you authenticate AKS with ACR?
142. What is the difference between ACR and Docker Hub?
143. How do you deploy a Dockerized .NET application to AKS?
144. Explain the flow from Dockerfile to AKS.
145. What happens when you update a Docker image used by an AKS deployment?
146. How do you implement rolling deployment with Docker and AKS?
147. How do you rollback a Dockerized application in AKS?
148. How do Docker containers, ACR, and AKS work together?

---

## 14. Scenario-Based Questions

149. You have two .NET microservices running in separate containers. How will they communicate?

150. Your Docker container starts and immediately stops. How will you troubleshoot it?

151. Your .NET API works on your machine but doesn’t work inside Docker. What could be the reasons?

152. Your Docker image is 1.5 GB. How would you reduce its size?

153. Your container cannot connect to SQL Server running in another container. How would you troubleshoot it?

154. You have 10 .NET microservices. How would you run them locally using Docker?

155. You need to run .NET API, SQL Server, Redis, and RabbitMQ locally. How would you design the Docker Compose setup?

156. Your application needs database credentials. How would you securely provide them to the container?

157. Your application receives a large amount of traffic. How would you scale containers?

158. You have multiple replicas of a .NET API. How would you distribute traffic between them?

159. How would you deploy a Dockerized .NET microservice to production?
