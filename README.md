AWS Java Basics - S3 - Basic S3 Operations 
===========================================
This repository is based on https://github.com/aws/aws-sdk-java/blob/master/src/samples/AmazonS3/S3Sample.java  
This script demonstrates how to make simple S3 API calls.   
By using this script, you agree to the the Terms and Conditions of products and services used.

Prerequisites
--------------
1.  Create an **AWS** account. Learn more about AWS here http://aws.amazon.com/getting-started/

2.  Create an **IAM** user with the required permissions to perform related operations. Learn more here --> http://docs.aws.amazon.com/IAM/latest/UserGuide/GSGHowToCreateAdminsGroup.html  
	
3.	Create an **Access Key** and **Secret Key** for the user. Learn more here http://docs.aws.amazon.com/IAM/latest/UserGuide/ManagingCredentials.html#Using_CreateAccessKey  
	Fill in your AWS access credentials in the provided credentials file template, and be sure to move the file to the default location (~/.aws/credentials) where the sample code will load the credentials from.  
	**WANRNING:** To avoid accidental leakage of your credentials, DO NOT keep the credentials file in your source directory. http://aws.amazon.com/security-credentials

4.  Download and install **JDK-EE** and **JEE** from http://www.oracle.com/technetwork/java/javaee/downloads/index.html

5.  Install **Eclipse IDE for Java EE Developers** from http://www.eclipse.org/downloads/
 
6.  Install **EGit** from http://download.eclipse.org/egit/updates/ to download code stored on Git.

7.  Open **Eclipse** and first update your IDE. **Help** > **Check for Updates**. Install any updates if available.

8.  Install **Install the AWS SDK for Java**. In **Eclipse** > **Help** > **Install New Software...** > In the resulting window, enter "http://aws.amazon.com/eclipse" under **Work with** and hit the Tab key. In the below window, select **AWS Toolkit for Eclipse** and click **Next**. Accept the defaults on the next screen and click on **Next**. Accept the license agreements after reading them and finally click on **Finish**.  

8.  Create a new project in Eclipse by selecting **File** > **New** > **Java Project** > Give the project a name > **Next** > **Finish**

7.  Right Click the newly created project and choose **New** > **Class** > Give the class a name Eg: Strings > Select **public static void main(String[] args)**

8.  Copy the code attached in the **Strings.java** file into newly created file.


Strings
------------

1.	From the Menu bar choose **Run As** > **Java Application** to execute the code. 

Support
-------------------
Use this script at your own risk.

a.	http://www.oracle.com/us/support/index.html  
b.	http://www.eclipse.org/forums/
