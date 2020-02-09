
This is all the files relating to CI/CD pipeline for 
Lesson 3 Udacity DevOps Nano Degree.


AWS Configration

1. You will need to create a EC2 pem key called "udacity"
2. You will need to create a User Role that will allow you to access EC2 and S3 services.

The two CF scripts will create a network and install an EC2 instance with Jenkins install on port 8080

There is an output in cloud formation of the URL of the Jenkins server

You will need the admin password which is located here on the EC2 instance you have just created.

/lib/jenkins/secrets/initialAdminPassword
