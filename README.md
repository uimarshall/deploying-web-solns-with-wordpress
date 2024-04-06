# Deploying a Web Solution with Wordpress

## Project Overview

This project aims to deploy a web solution using WordPress on Ubuntu servers hosted on Amazon EC2 instances. It involves setting up two EC2 instances, configuring block devices, creating logical volumes, installing WordPress, and configuring a MySQL database server.

## Prerequisites:

- Access to an AWS account with permissions to create EC2 instances and manage security groups.

- Basic familiarity with the Linux command line.

- Understanding of web server configurations and WordPress installation.

## Step-by-Step Implementation:

### Step 1 - Launch and Configure EC2 Instances:

- Create two Ubuntu EC2 instances and set the `Configure storage` to `10`.

- Configure Security group to allow inbound traffic on ports 22 (SSH) and 80 (HTTP) for the web server, and port 3306 (MySQL) for the database server.

![alt text](images/image.png)
