# Host a static website in amazon's cloud for dirt cheap!
In this exercise you're tasked to:

- Make a website that is hosted on [AWS](https://aws.amazon.com/) (Amazon Web Services) using Simple Storage Service (S3).
- Configure AWS infrastructure in the AWS console
- Create a deployment pipeline using [CircleCI](https://circleci.com/signup/) to auto-magically update the website from changes in GitHub.

## What will you learn?

- S3 and bucket policies to store files publicly. 
- [Circleci](https://circleci.com/signup/) as a continuous deployment pipeline. 
- Git committing and pushing changes to GitHub 
- Structure a webpage using [HTML](https://www.w3schools.com/html/html_basic.asp) / [CSS](https://www.w3schools.com/css/default.asp).

## How will it work
![Design Diagram](https://github.com/StevenR152/AWS-Frontend-on-S3-Exercise/blob/master/S3WebsiteArchitecture.png?raw=true)

## Steps
Let's get started:

1) Create a [GitHub](https://github.com) repository containing a hello world [html](https://www.w3schools.com/html/html_basic.asp) file (optional: that links a [css](https://www.w3schools.com/css/default.asp) file to change font size).
2) Log into the AWS Console 
  3) Navigate to the S3 Service and start creating a bucket
  4) On the first screen enter a bucket name. Note: Bucket names are unique for all users on the planet.
  5) Skip page 2, these options are not too important right now.
  6) On option screen 3, make sure to unselect all of the "Block Public Access" option.
7) Use [Circleci](https://circleci.com/signup/) to deploy all code changes to the S3 storage bucket when changed. Use the docs to understand [Circleci](https://circleci.com/) then the [example](https://github.com/StevenR152/AWS-Frontend-on-S3-Exercise/blob/master/config.yml) might help you deploy your website to your S3 bucket.
8) Add a policy making the bucket publicly accessible. An example bucket policy can be found [here](https://github.com/StevenR152/AWS-Frontend-on-S3-Exercise/blob/master/bucketpolicy.json)
[html](https://www.w3schools.com/html/html_basic.asp)
9) In AWS Console on S3 browse into your bucket, and select the index.html file. On the right properties tab there is a URL for accessing your bucket.
10) Commit and push changes to the repository that makes the webpage contain different content or link in a [css](https://www.w3schools.com/css/default.asp) file to style the page. 

