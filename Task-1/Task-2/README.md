# Task 2 - Deploy a Virtual Machine & Install Web Server

## Objective

Launch an Ubuntu EC2 instance and configure an Apache web server to host a custom webpage.

## Services Used

* Amazon EC2
* Ubuntu Server 26.04 LTS
* Apache2 Web Server

## Steps Performed

1. Created an Ubuntu EC2 instance.
2. Configured security group rules to allow SSH and HTTP traffic.
3. Connected to the instance using EC2 Instance Connect.
4. Installed Apache web server.
5. Enabled and started the Apache service.
6. Created a custom webpage displaying "Hello from Cloud VM".
7. Accessed the webpage using the public IP address.

## Commands Used

```bash
sudo apt update
sudo apt install apache2 -y
sudo systemctl enable apache2
echo "<h1>Hello from Cloud VM</h1>" | sudo tee /var/www/html/index.html
```

## Public IP

13.200.250.242

## Outcome

Successfully deployed a virtual machine on AWS EC2 and hosted a custom webpage accessible through the public IP address.
