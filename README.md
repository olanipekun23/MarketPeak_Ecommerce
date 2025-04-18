# MarketPeak Ecommerce

An Ecommerce platform for managing Products, orders, and Customers.


## Features

- Product Management
- Order Processing
- Customer Accounts



# Capstone Project: E-Commerce Platform Deployment with Git, Linux, and AWS

**Abstract**

This capstone project focuses on deploying a static e-commerce website using Git, Linux, and AWS. It demonstrates proficiency in version control, cloud computing, and web server configuration. The project follows a structured approach, including repository setup, website deployment, and continuous integration for updates. The final implementation ensures a scalable and accessible web presence hosted on AWS.

**Description**

This project demonstrates the skills and knowledge I have acquired in setting up and deploying a static website using Git, Linux, and AWS. It showcases my ability to implement version control through Git, manage a structured development workflow, and deploy applications in a cloud environment. The project involves creating and managing branches, staging, committing, and pushing changes to a remote repository, as well as configuring and hosting the website on an AWS EC2 instance. Detailed snapshots of the commands executed and tasks performed are included for documentation and transparency. This capstone project reinforces my expertise in Git operations, Linux server management, and cloud deployment, key skills essential for modern DevOps practices.


# Objective

- Implement Version control using GIT.

- Host a Static e-commerce website using AWS Ec2.

- Automate Deployments using Git workflow.

- Secure and optimize the server configuration for better performance.

# Tools and Technologies Used


- Version Control: Git, GitHub


- Cloud Services: AWS EC2.


- Operating System: Linux (Ubuntu/CentOS)


- Web Server: Apache


- Development Tools: CLI, SSH


- Programming Languages: HTML, CSS, JavaScript (if applicable)

## Setup

Instructions on how to set up and run the proj Step by Step.

1. VERSION GIT CONTROL
 
    Creating Local Repository
    ![init repo](image.png)


    Downloading Website Template


    ![web template](image-1.png)

    Stage and Commit the Website Template to Git

    set Global User Name and e-mail.

    ![global config](image-2.png)

    git add to stage

    ![git add](image-3.png)

    git commit -m to commit files


    ![git commit](image-4.png)

    status

    ![status](image-5.png)


    Git push to push to the new Repository

    ![git push](image-6.png)


    New Repository

    ![new Repository](image-7.png)
    

2. AWS DEPLOYMENT

    Setting Up AWS Ec2 Instance

    loggin On to AWS console

    ![AWS console](image-8.png)

    Launch a New Ec2 Instance

    ![Ec2 Launch](image-9.png)

    ![setup](image-10.png)

    Configuration Using Ubuntu AMIs

    ![configuration](image-11.png)

    ![Launching](image-12.png)

    ![success](image-13.png)

    ![success](image-14.png)

    CONNECTING to Ec2 Instance Using SSH

    ![SSH](image-15.png)


    CONNECTED


    ![SSH connected](image-16.png)

    ![SSH Logged in](image-17.png)

    Key-Gen for Connecting Ec2 Instance to Github

    ![key-gen](image-18.png)

    ![New Key](image-19.png)

    Copying Github SSH Adress

    ![Adress/link](image-20.png)

    Entering New SSH Key-Gen

    ![Adding new key](image-21.png)

   

     ## Git Cloning Using SSH

    clone Git Repository on AWS Serve


    ![git clone](image-22.png)

    ## INSTALLING WEB SERVER ON Ec2 INSTANCE


    Updating All Packages

    ![packages](image-23.png)

    Install and start apache server

    ![apache server](image-24.png)

    ## Configure Apache Server
    
    
    Prepare Server by Clearing Default HTTPD Web Directory and Replace with Market Peak E-Commerce Files

    ![configuration](image-25.png)

    Reload Apache Server

    ![reload](image-26.png)

    Updating Apache Url to 2013_waso_strategy

    ![url](image-27.png)

    ## Access the Website through Web Browser

    Copy Public IP and Open in a Browser

    ![web page](image-28.png)

    ## Continuous Integration and Deployment


    Creating a Development Branch

    ![branch](image-29.png)

    ![changes](image-30.png)

    Making and Deploying Changes

    ![deploying](image-31.png)

    ![commit](image-32.png)

    ![git push](image-33.png)

    Git Checkout origin main

    ![checkout](image-34.png)

    Creating a pull Request

    ![request](image-35.png)

    ![create](image-36.png)

    ![confirm PR](image-37.png)

    UPDATING ORIGIN 

    ![update](image-38.png)


    ## Testing Changes

    Website After Changes

    ![web](image-39.png)


    ## Results & Testing

   - The website is successfully hosted on AWS.


   - The Git repository enables version control and easy updates.


   - Continuous integration ensures smooth deployment.


   - The website is accessible via the EC2 instance’s public IP.



    
    ## Challenges & Solutions


    ### Challenges Faced:

   - Trying too effect changes from the Production server side.


   - Knowing the policies for my server to be able to access via web browser.


   - Git merge conflicts during updates.

    ## Solutions Implemented:


   - I used the changes that were git pulled from my remote repository to update apache url location(\var\www\html).


   - Made sure my server allowed web traffic on port 80.


   - Resolved conflicts by managing Git branches efficiently.

    ## Conclusion

    The Market Peak E-Commerce Website project successfully demonstrates cloud deployment, Git-based version control, and continuous integration. Future improvements included.















