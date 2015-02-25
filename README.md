AWS Java Basics - S3 - Basic S3 Operations 
===========================================
This repository is based on https://github.com/aws/aws-sdk-java/blob/master/src/samples/AmazonS3/S3Sample.java  
This script demonstrates how to make simple S3 API calls.   
By using this script, you agree to the the Terms and Conditions of products and services used.

Prerequisites
--------------
1.  Create an **AWS** account. Learn more about AWS here http://aws.amazon.com/getting-started/

2.  Create an **IAM** user with the required permissions to perform related operations. Learn more here http://docs.aws.amazon.com/IAM/latest/UserGuide/GSGHowToCreateAdminsGroup.html  
	
3.	Create an **Access Key** and **Secret Key** for the user. Learn more here http://docs.aws.amazon.com/IAM/latest/UserGuide/ManagingCredentials.html#Using_CreateAccessKey  
	Fill in your AWS access credentials in the provided credentials file template, and be sure to move the file to the default location (~/.aws/credentials) where the sample code will load the credentials from.  
	**WANRNING:** To avoid accidental leakage of your credentials, DO NOT keep the credentials file in your source directory. http://aws.amazon.com/security-credentials

4.  Download and install the latest versions of **JDK-EE** and **JEE** from http://www.oracle.com/technetwork/java/javaee/downloads/index.html

5.  Install **Eclipse IDE for Java EE Developers** from http://www.eclipse.org/downloads/
 
6.  Install **EGit** from http://download.eclipse.org/egit/updates/ to download code stored on Git.

7.  Open **Eclipse** and first update your IDE. Choose **Help** > **Check for Updates**. Install any available updates.

8.  Install the **AWS SDK for Java**. In **Eclipse** > click on **Help** > **Install New Software...** > In the resulting window under **Work with**, enter "http://aws.amazon.com/eclipse" and hit the Tab key. In the below window, select **AWS Toolkit for Eclipse** and click **Next**. Accept the defaults on the next screen and click on **Next**. Accept the license agreements after reading them and finally click on **Finish**.  

9.  To run this programme in Eclipse, you can follow either one of the below metnioned methods.  
  	a. In Eclipse click **File** > **New** > **Java Project** > Give the project a name **S3Sample** > **Next** > click on **Libraries** > **Add Library..** > select **AWS SDK for Java** click **Next** and **Finish**. Click **Finish** again.  
	Right click the S3Sample project and select **New** > **Class**. Name the class **S3Sample**. Replace the contents of the S3Sample class with the contents of the attached S3Sample.java file.  
	b. In Eclipse **File** > **Import** > under **Git** > select **Projects from Git** and click **Next**. Select **CloneURl** and click **Next**. In the next window enter "https://github.com/KarthikChandy/Java-AWS-S3Sample.git" in the **URl** text box. Accept the defaults and click on **Next**. Select your local Git directory using the Brownse button and click **Next** > **Next** and **Finish**.

Run S3Sample.java
-----------------
Look for **S3Sample.java** by expanding your project > src > default. Right click **S3Sample.java** and select **Run As Java Application** to execute the code. You should find the output under the **Console** tab in Eclipse.

Support and Referrences
-----------------------
Use this script at your own risk.

a.	http://www.oracle.com/us/support/index.html  
b.	http://www.eclipse.org/forums/  
c.	https://aws.amazon.com/premiumsupport/  
d.	http://aws.amazon.com/sdk-for-java/  
e	http://aws.amazon.com/eclipse/
