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

### EC2 Instance Running
<img width="1848" height="807" alt="Screenshot 2026-06-24 003320" src="https://github.com/user-attachments/assets/3d314d74-f5b0-4bbc-b135-15ee25e2d475" />


### Docker Container Running
<img width="1895" height="992" alt="Screenshot 2026-06-24 002123" src="https://github.com/user-attachments/assets/cb3d969b-d179-4786-b19f-2306b0292dbe" />


### Nginx Output
<img width="1528" height="587" alt="Screenshot 2026-06-24 001853" src="https://github.com/user-attachments/assets/d1ebe725-2b8d-46d5-9bc6-e175b7df6605" />


