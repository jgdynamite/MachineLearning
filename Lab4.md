# Lab4 HowTO

At this point you should have all you files in an AWS S3 bucket ready for Data Science work. 
The following steps will walk you through all the processes required for this part of the lab.

## Step 1: Launch an Amazon SageMaker Notebook Instance
a. Open the AWS management console, ***search*** and ***select SageMaker***.

![Console Screenshot](https://s3.amazonaws.com/recommendation-48/MacDown/AWS_Management_Console-2.png)

b. From the SageMaker dashboard, click ***create notebook instance***

![ SageMaker Console](https://s3.amazonaws.com/recommendation-48/MacDown/Amazon_SageMaker.png)

c. On the create notebook instance page, do the following:

1. Give your notebook instance a name your will remember.
2. Select ml.m4.16xlarge for notebook instance type.
3. For your IAM role - select **create a new role** from the drop down menu.
 
![Console Screenshot](https://s3.amazonaws.com/recommendation-48/MacDown/Amazon_SageMaker-4.png)

d. Select ***any S3 bucket*** from the pop-up dialogue box and ***create role***

![Console Screenshot](https://s3.amazonaws.com/recommendation-48/MacDown/Amazon_SageMaker-5.png)

e.	Amazon SageMaker will create a new role for you and pre-select that role. Next ***create notebook instance***.
![Console Screenshot](https://s3.amazonaws.com/recommendation-48/MacDown/Amazon_SageMaker-6.png)

f.	If you are here, your instance is launching; thus in ***pending*** status. You should be able to access your notebook in less than 5 mins. 
![Console Screenshot](https://s3.amazonaws.com/recommendation-48/MacDown/Amazon_SageMaker-12.png)

## Step 2: Accessing your notebook instance
a.	To access your notebook, kindly wait until your instance status is ***InService*** and click ***open***.
![Console Screenshot](https://s3.amazonaws.com/recommendation-48/MacDown/Amazon_SageMaker-11.png)

b. Your notebook landing page should be similar this below:

![Console Screenshot](https://s3.amazonaws.com/recommendation-48/MacDown/Home.png)

c. Open a terminal by clicking on **New** and then **Terminal**

![Console Screenshot](https://s3.amazonaws.com/recommendation-48/MacDown/Home-3.png)

d. Run the following commands in your terminal (**copy, paste and press enter**) and ensure to follow the instructions on your terminal screen.

```
wget https://s3.amazonaws.com/dallas-ai-day/SageMaker-Reco/Helper.sh
sh Helper.sh.sh
```
e. After running both commands above, your output should be similar to this:
![Console Screenshot](https://s3.amazonaws.com/recommendation-48/MacDown/Mozilla_Firefox.png)

f. Return to your notebook landing page by selecting your browser tab titled **Home**. Click on the **Movie_Recommender_Commented_final.ipynb** notebook and proceed with the instructions in the notebook.  
![Console Screenshot](https://s3.amazonaws.com/recommendation-48/MacDown/Home-5.png)

