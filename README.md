# [AWS](https://aws.amazon.com/) Frontend Exercise 1: Host a static website in S3 for dirt cheap!
In this exercise you're tasked to:

- Make a website that is hosted on [AWS](https://aws.amazon.com/) (Amazon Web Services) using Simple Storage Service (S3).
- Configure AWS infrastructure using The AWS management console.
- Create a deployment pipeline using [CircleCI](https://circleci.com/signup/) to auto-magically update the website from changes in GitHub.

## What will you learn?

- S3 and bucket policies to store files publicly. 
- [Circleci](https://circleci.com/signup/) as a continuous deployment pipeline. 
- Git committing and pushing changes to GitHub 
- Infrastructure as code with terraform. 
- Structure a webpage using [HTML](https://www.w3schools.com/html/html_basic.asp) / [CSS](https://www.w3schools.com/css/default.asp).

## Steps
Let's get started:

1) Create a [GitHub](https://github.com) repository containing a hello world [html](https://www.w3schools.com/html/html_basic.asp) file (optional: that links a [css](https://www.w3schools.com/css/default.asp) file to change font size).
2) Use the AWS Management Console to create a [AWS](https://aws.amazon.com/) S3 storage bucket that will hold the website's files. 
3) Use [Circleci](https://circleci.com/signup/) to deploy all code changes to the S3 storage bucket when changed. Use the docs to understand [Circleci](https://circleci.com/) then the [example](https://github.com/codersuk/AWS-Exercise-Frontend-on-S3/blob/master/config.yml) might help you deploy your website to your S3 bucket.
4) Update your S3 bucket in amazon to add a policy making the bucket publicly accessible. Don't forget to attach the bucket to the policy. You can browse the AWS Management Console S3 service to see the Policy is on the bucket. [Example Policy](https://github.com/codersuk/AWS-Exercise-Frontend-on-S3/blob/master/bucketpolicy.json)
5) View the [html](https://www.w3schools.com/html/html_basic.asp) file using the public url which is found on the html files properties tab (visible within the [aws](https://aws.amazon.com/) user interface). 
6) Commit and push changes to the repository that makes the webpage contain different content or link in a [css](https://www.w3schools.com/css/default.asp) file to style the page. 

