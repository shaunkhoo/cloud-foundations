# Session 1: Everything about EC2

## Overview

To kickstart our cloud foundations training, we start with one of the most fundamental services on the cloud: virtual machines. Elastic Compute Cloud (otherwise known as EC2) is one of AWS's first services and remains one of its top products today.

## What you will learn

* Set up an EC2 instance on AWS
* Configure the EC2 instance correctly for secured access
* Install applications on EC2 and access them remotely

## Materials

> If you are completely new to AWS or cloud computing, please start with the introductory resources first. You can find them on the main page.

* **AWS SA Course:** Section 5: EC2 Fundamentals, all videos (approx 1-2h)
* Other related stuff:
    * **Vim:** The hands-on will require you to use Vim, a native Linux text editor. [This lecture](https://missing.csail.mit.edu/2020/editors/) will be helpful in understanding how to use it.
    * **SSL:** [This article](https://www.cloudflare.com/learning/ssl/what-is-ssl/) explains why we create certificates to enable HTTPS connections to our Jupyter Notebook. [This one](https://sectigostore.com/page/what-is-a-self-signed-certificate/) explains why Chrome displays a warning even when you're using HTTPS.

## Hands-on Session

For this hands-on session, we will be mainly following [Chris Albon's walkthrough](https://chrisalbon.com/aws/basics/run_project_jupyter_on_amazon_ec2/) on running Jupyter Notebook on EC2. We have added on a few other steps to cover some finer points about EC2 as well.

**Follow these steps for the hands-on session:**

* Spin up an EC2 instance using the AWS Console
* Expose your EC2 instance to the Internet, but only to your IP address
* SSH (tunnel) into your EC2 instance remotely
* Install Jupyter Notebook and configure it for remote access
* Test your setup by running code on your Jupyter Notebook
* Stop (not terminate) and restart your instance
* Tear down all the resources correctly using the AWS Console

**Why is this useful?**
* Covers a lot of fundamentals needed for EC2, such as selecting the right instance, connecting to it, and securing it correctly.
* Jupyter Notebook is just like any application. Once you can do this, you can install and run any other applications on EC2 (RStudio, Airflow, Kubernetes etc)