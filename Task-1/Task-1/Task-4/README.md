# Task 4 - Deploy a Docker Container on Cloud VM

## Objective
Deploy a Docker-based web application on AWS EC2 using Docker and expose it to the internet.

## Services Used
- AWS EC2
- Docker
- Nginx

## Commands Used

```bash
sudo apt update
sudo apt install docker.io -y
sudo systemctl start docker
sudo docker run -d -p 8080:80 --name nginx-container nginx
sudo docker ps
```

## Public URL

http://13.233.107.66:8080

## Output

Nginx default page successfully accessible through public IP.

## Screenshots

- EC2 Instance Running
- Docker Container Running
- Nginx Output Page
