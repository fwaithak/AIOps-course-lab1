\# Lab 1 — Getting Started with Docker



\*\*Course:\*\* 04800 Special Topics: AIOps Observability, Spring 2026  

\*\*Points:\*\* 100 | \*\*Due:\*\* March 17, 2026



\## Overview

This lab covers foundational Docker skills including building and running 

containers, managing images and volumes, using Docker Compose, and deploying 

the Google Online Boutique microservices application using Skaffold.



\## Screenshots



| # | File | Description |

|---|------|-------------|

| 1 | 01\_our\_application.png | `docker ps` and `docker image ls` output alongside the running Todo app with items added |

| 2 | 02\_updating\_app.png | Todo app with modified title in CAPS demonstrating live container rebuild |

| 3 | 03\_sharing\_app.png | Docker Hub showing successfully pushed image under waithaka001/lab1-getting-started |

| 4 | 04\_persisting\_db.png | Docker Desktop Volumes panel showing the todo-db named volume |

| 5 | 05\_bind\_mounts.png | Container running with bind mount; testfile.txt visible in host app directory |

| 6 | 06\_docker\_compose.png | `docker compose ps` output showing multi-container app running |

| 7 | 07\_remote\_container.png | Shell session inside container: env vars (MYSQL\_\*), process list, and MySQL connection confirmed |

| 8 | 08\_boutique\_image\_ls.png | Full set of Boutique microservice images locally rebuilt via Skaffold (tagged sic-jss-475-g11a66b24) |

| 9 | 09\_boutique\_homepage.png | Online Boutique frontend running at localhost:8080 using local Docker images |

