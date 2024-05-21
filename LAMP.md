#web-stack-implementation

Hello!! This is a Web Stack Implementation Project.

What is a Web Stack?
The term "web stack" typically refers to the combination of software and technologies used to develop and run web applications. It consists of several layers(e.g. OS system, webserver, script interpreter, and database), each serving a specific purpose in the process of building and delivering web applications.One of the most popular web stacks include LAMP, which stands for **Linux, Apache, MySQL, and PHP**. The LAMP stack will be used for this project!


##LINUX

###Setting up ypur virtual environment

Linux is an operating system that manages the underlying hardware on your PC. It is an open-source software that is used worldwide. It is flexible and easy to configure.

In order to complete this project, it is necessary to set up a virtual environment. In order to achieve this, first, create a free [AWS account](https://aws.amazon.com/) and then create a virtual server using the Ubuntu Server OS. More details to come shortly!

AWS offers a Free Tier for newly registered account users. This enables users to try out some AWS services free of charge within certain usage limits. For this project, we will utilize the [EC2 (Elastic Compute Cloud)](https://aws.amazon.com/ec2/features/) service, which is covered by the Free Tier!

####Let's get started!

Begin by registering and setting up an [AWS account](https://aws.amazon.com/) and following the directions on the screen. Once you have created your AWS account, navigate to the login page and type in your credentials.

![](./images/aws.png)

Once you have signed-in to your AWS account, navigate to the top-right of the screen and select your preferred region (this should be the closest region to your physical location).
![](./images/aws2.png)

After you have selected your region, navigate to the search bar and type in EC2. Select the EC2 service that appears.
![](./images/aws3.png)
Next, click on "Launch Instances".

Now we are going to configure our EC2 instance! Select the Ubuntu Server 24.04 LTS (HVM) as the Amazon Machine Image (AMI).

![](./images/aws4.png)

Then, select "t3.micro" as the instance type. 
![](./images/aws5.png)

Once you have made the selection, click "Launch".
![](./images/aws6.png)