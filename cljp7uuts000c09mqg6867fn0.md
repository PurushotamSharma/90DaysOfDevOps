---
title: "Amazon EC2"
datePublished: Wed Jul 05 2023 04:26:01 GMT+0000 (Coordinated Universal Time)
cuid: cljp7uuts000c09mqg6867fn0
slug: amazon-ec2
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1688531134594/a6a218ac-3167-4926-bfa1-6d0a71ed97d4.jpeg
tags: ec2, linux, aws, devops, trainwithshubham

---

## Introduction:

Hello Everyone, Welcome to my new blog today we will be discussing one of the Amazon Services which is the EC2. AWS is the cloud provider platform that provides many services in the cloud. Today we will be discussing the Amazon Elastic Compute Engine.

### What is the Amazon EC2?

**Amazon EC2 stands for the Amazon Elastic Compute Engine i**s a web service that provides a secure, resizeable compute capacity in the cloud. By using Amazon EC2 you can create multiple virtual machines very frequently and at low cost.

![Step by Step Creation of an EC2 Instance in AWS and Access it via… –  Towards AI](https://cdn-images-1.medium.com/max/360/0*uGnkedWzlM-J1bYC align="left")

### How to Launch the Instance using EC2 on AWS?

Here we will be discussing all the steps for launching any Instance on the EC2.

### Step:1

Login to your AWS account or AWS console. If you did not have an account on AWS then create an AWS account. It is very simple.

For the login, you see this type of the Screen

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1687856218037/09e41d9e-a058-4b23-af1b-7fbcc934df36.png align="center")

Here are 2 ways to log in. One is by the root user and the second is by using the IAM user.

So what is the root user, When you create an AWS account, you begin with **one sign-in identity that has complete access to all AWS services and resources in the account**. This identity is called the AWS account root user and is accessed by signing in with the email address and password that you used to create the account.

An AWS Identity and Access Management (IAM) *user* is an entity that you create in AWS. The IAM user represents the human user or workload who uses the IAM user to interact with AWS. A user in AWS consists of a name and credentials.

An IAM user with administrator permissions is not the same thing as the AWS account root user.

So here we will be signing as the root user. After logging you will see this type of screen.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1687856897427/6b3745ed-994c-4d84-ab17-3178a2eef856.png align="center")

Here you have to search the EC2 in the search bar and click on that.

After Opening the EC2 service you will see the Launch Instance button on the left

bottom

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1688528853595/1a9c9a8f-752f-4dc6-9834-a85d0fc87153.png align="center")

Click on the launch Instance.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1688529157341/69167187-47a7-4129-bad3-377139c8be7a.png align="center")

**Name:** In the name section you have to write your server name

Eg. MyLinux Server, MyLinux any name that you want to give to your instance.

Here I will name it Demo AWS

**Number of Instances:** In this section, you have to write how many instances you want to create. Like you have to create 1 or 2 or 3.

Here I select 1 Instance.

**Application and OS images(Amazon Machine Image):** This is the main part of your instance here you want to choose which os you want in your Instance,

Such as Amazon Linux, Ubuntu, Windows, Mac etc.

Here I am going to select Ubuntu.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1688529552978/5fed3bed-ab3a-4413-bceb-12f4a277805c.png align="center")

Here I selected the Ubuntu 22.04 Lts version.

here 22 is a year and the 04 is the Month. and LTS meaning is **Long Term Support.**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1688529650278/9a9912cb-a5c7-473b-afd1-08ef9a0cb432.png align="center")

**Instance Type:** Instance types comprise **varying combinations of CPU, memory, storage, and networking capacity** and give you the flexibility to choose the appropriate mix of resources for your applications.

Here I am selecting the t2.micro which is free and in this, we will get 1 CPU and 1GiB memory.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1688529784531/532ade93-cb3d-4d80-9e89-620cecbd001f.png align="center")

**Key pair :** A key pair is **a combination of a public key that is used to encrypt data and a private key that is used to decrypt data**. For more information about key pairs, ensure you are signed into the AWS console and then review Amazon EC2 Key Pairs in the Amazon EC2 User Guide for Linux Instances.

In simple words, we can say that is the key to your server.

Let's understand by the example.

If you create the Instance whenever you want to log in you will go to AWS and log in. Without using Key pair you can not log in to your instance because this is your server for Security purposes you have to create your key pair so nobody can log in to your server.

here you can choose any existing key pair or you can create new key pair.

Here I am creating the New Key Pair.

After clicking on the Create new key pair you will see this type of screen.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1688530140027/7880276d-ad19-4c31-b16d-04e850403861.png align="center")

Firstly you have to enter your key pair name here I am giving the name Linuxkey.

after that, you have to select the type of key pair

Now you have to select the file format of your key.

If you want to launch your instance using OpenSSH then you have to select the .pem file and you want to launch the Instance using putty the .putty file format.

Now click on the create key pair after clicking this key will automatically download in your Pc.

For the network setting we will discuss in the next blog here we will leave default only.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1688530496098/b4daf225-dd8f-4551-923d-bf9f92745eee.png align="center")

Now click on the Launch Instance.

Congrats you have launched your first Instance using EC2.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1688530555790/e9099688-737f-4421-aa05-b5080c40a7eb.png align="center")

Thanks for reading the Blog.

## Happy Learning.))