# Static Web Hosting with S3 and CloudFront
* Cloudformation template for static website hosting on S3 with CloudFront

## Features
* Automate build with CodeCommit, CodePipline and CodeBuild.
* Uses Cloudfront to improve content delivery performance.
* S3 and S3 redirect setup for base and www domain with Route53.

![Imgur](https://i.imgur.com/djiSTmj.png)

## Getting Started
To begin using this site, choose one of the following options to get started:
* Clone the repo: `git clone https://github.com/barrygithub/cloudformation-s3-website.git`
* Fork the repo.

## Start the project

1. Upload template through Cloudformation console to start.
2. When prompted in event viewer, verify certificate with Certificate Manager and Route53.
3. Once finished, clone repository from CodeCommit.
4. Insert buildspec.yml(example included in example-spec folder) with your site files.
5. Push index.html and site files to your new repository to automate build.