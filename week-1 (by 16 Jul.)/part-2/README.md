# Week 1 Part 2

## Introduction to Amazon Web Service (AWS)

Amazon Web Service (AWS) is the most popular cloud service in the world. Today we should use AWS as infrustructure for web server.

### Create Account on AWS

Go to [AWS official website](https://aws.amazon.com/). Create your account on AWS.

### Create Instance on Amazon Elastic Compute Cloud (Amazon EC2)

Create an instance on Amazon EC2 which should meet following requirements:

1. Instance type should be **t2.micro**.
2. Machine image should be **Amazon Linux AMI**. (2018 version is prefered)
3. Attach **8GB General Purpose SSD** storage at least.

### Associate Elastic IP with Instance

Find the **Elastic IPs** service in Amazon EC2. Create a public IP and associate it with your instance.

### Connect and Manage Instance

Find a way to connect to your Amazon EC2 instance and manage it by command line interface.

### Install Node.js

Find a way to install Node.js on your instance.

### Build Node.js Project for Web Server

Build your first Node.js project for web server on your instance. Just as before, you should use **Express.js** as a solution, but binding to **80 port**. Finally, we can check your website by entering URL `http://[YOUR_PUBLIC_ELASTIC_IP]/` in the browser's address bar.

**Write down your website URL in README.md file.**

### Build Working Flow

Everytime you hand in assignment, I will check your **GitHub repository** and **website URL**. So, build a working flow between your local machine and cloud environment, which can be supported by **Git** and **GitHub**.