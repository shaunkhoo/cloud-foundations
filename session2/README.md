# Session 2: Storage made Simple

## Overview

Now that you know how to provision an EC2 instance, it's time to understand the various storage options accessible from your instance — and any other AWS services.

## What you will learn

* Choosing the right AWS storage service
* Create S3 buckets
* Upload, delete, and version objects in S3 buckets
* Encrypt S3 bucket objects
* Secure S3 buckets using ACLs and bucket policies
* Create a static website hosted on S3
* Grant cross-origin access to your S3 bucket

## Materials

> If you are completely new to AWS or cloud computing, please start with the introductory resources first. You can find them on the main page.

* **Udemy Course:**  Section 12: Amazon S3 Introduction, all videos (approx 1h).
* **Udemy Course (optional):** Section 7: EC2 Instance Storage, all videos (approx 1h).

You can access the [Udemy course](https://www.udemy.com/course/aws-certified-solutions-architect-associate-saa-c02/) through [CSC's Learn App](https://learn.gov.sg/).

## Hands-on Session

> Find the slides for the hands-on session [here](https://docs.google.com/presentation/d/19suCETn2IbpwLgZHh75bBzp56IqKCdElGk1vPZAdmr4/edit?usp=sharing)

**Follow these steps for the hands-on session:**

* Set up an S3 bucket
* Create and delete versions in the S3 bucket
* Encrypt objects in the S3 bucket
* Upload and download from S3 with Boto3
* Configure the S3 bucket for public access
* Set up a static website with S3
* Tear down all the resources correctly using the AWS Console

**Why is this useful?**
* Learn how different AWS storage services differ, and when to use which service.
* Covers the basics of creating, accessing, securing and encrypting S3 buckets.
* Having configured your S3 buckets, you can use it to store data while exploiting features of the cloud, including high availability and durability at potentially infinite scale.