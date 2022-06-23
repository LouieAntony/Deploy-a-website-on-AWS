# Deploy_a_website_on_AWS

AWS, which is Amazon Web Services, is a platform that offers flexible, reliable, scalable, easy-to-use and cost-effective cloud computing solutions.
AWS is a comprehensive, easy to use computing platform offered by Amazon. The platform is developed with a combination of infrastructure as a service (IaaS), platform as a service (PaaS) and packaged software as a service (SaaS) offerings.
Amazon Web Services offers a wide range of different business purpose global cloud-based products. The products include storage, databases, analytics, networking, mobile, development tools, enterprise applications, with a pay-as-you-go pricing model. 

Some of the Cloud Compute Services offered by Amazon are:

1. EC2 (Elastic Compute Cloud) - EC2 is a virtual machine in the cloud on which you have OS level control. You can run this cloud server whenever you want.
2. LightSail - This cloud computing tool automatically deploys and manages the computer, storage, and networking capabilities required to run your applications.
3. Elastic Beanstalk - The tool offers automated deployment and provisioning of resources like a highly scalable production website.
4. EKS (Elastic Container Service for Kubernetes) - The tool allows you to Kubernetes on Amazon cloud environment without installation.
5. AWS Lambda - This AWS service allows you to run functions in the cloud. The tool is a big cost saver for you as you pay only when your functions execute.

## Workflow

<p align="center">
  <img src="pic/workflow.png">
</p>

### Creating a S3 bucket on AWS :

Step 1 : Search for S3 in the search bar and select S3 under services

![alt text](pic/1.png)

Step 2: Select the “Create bucket” option

![alt text](pic/2.png)

Step 3 : Create a bucket by filling in the details that are required such as name, region, public access etc. and click create bucket.

![alt text](pic/3.png)

![alt text](pic/4.png)

![alt text](pic/5.png)

Once the bucket has been successfully created you will see a green banner appear on top stating the same as you can see below.

![alt text](pic/6.png)

Step 4 : Click on your bucket name and you can see various options related to your bucket.

![alt text](pic/7.png)

Step 5 : Upload your project files into the bucket by selecting the “Add files” option and select upload.

![alt text](pic/8.png)

You can then see the files that have been uploaded as it says “Succeeded” next to each file that has been uploaded. 

![alt text](pic/9.png)

### Creating an EC2 instance on AWS :

Step 1: To create an EC2 instance, first click the services option and then click the EC2 option.

![alt text](pic/10.png)

Step 2: Click the launch instance option.

![alt text](pic/11.png)

Step 3: Fill in the details for Name and instance type.

![alt text](pic/12.png)

Step 4: In The key pair option, select create new key pair and a new pop up window will appear. 

![alt text](pic/13.png)

Step 4.1: Enter the “Key pair name” and select “Create key pair”. A key pair file will get downloaded which is to be kept private and safe.

![alt text](pic/14.png)

Step 5: Follow along the “Network Settings” and “Configure Storage” as follows and select “Launch instance”

![alt text](pic/15.png)

![alt text](pic/16.png)

Step 6: You will see that the instance has been created successfully on a green banner.

![alt text](pic/17.png)

### Connecting to the EC2 instance

Step 1: We first have to generate the putty key generator by loading the private key that was downloaded.

![alt text](pic/18.png)

Step 2: Copy the link that is provided in the 4th point in the window and use it to connect by using the terminal.

![alt text](pic/19.png)

![alt text](pic/20.png)

You will be able to see that all the dependencies have been installed and the connection process is complete.

Step 3: Click on the https link that has been provided and it will redirect you to a new webpage and you will be able to see that your website has been hosted. 

![alt text](pic/21.png)

![alt text](pic/22.png)

![alt text](pic/23.png)
