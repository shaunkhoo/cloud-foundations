# Session 1: Everything about EC2

## Overview

To kickstart our cloud foundations training, we start with one of the most fundamental services on the cloud: virtual machines. Elastic Compute Cloud (otherwise known as EC2) is one of AWS's first services and remains one of its top products today.

## What you will learn

* Set up an EC2 instance on AWS
* Configure the EC2 instance correctly for secured access
* Stop and start 

## Materials

> If you are completely new to AWS or cloud computing, please start with the introductory resources first. You can find them on the main page.

* **AWS SA Course:** Section 5: EC2 Fundamentals, all videos (approx 1-2h)
* Optional stuff:
    * 

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