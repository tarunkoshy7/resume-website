[![CI](https://github.com/tarunkoshy7/resume-website/actions/workflows/ci.yml/badge.svg)](https://github.com/tarunkoshy7/resume-website/actions/workflows/ci.yml)

# My Resume Website

## Overview

I decided to do this project as part of the Cloud Resume Challenge to get some hands on experience on AWS
after obtaining my AWS Solutions Architect Associate Certification. It's a work in progress at the moment
and will update this README as and when improvements are made.

Current Progress:

* Website hosted on an S3 bucket (public access blocked)
* CloudFront as CDN
* Only CloudFront distribution allowed to access S3 bucket
* Domain name, DNS managed on route 53
* Certificates on AWS Certificate Manager
* Code vulnerability scanning when raising a Pull Request with Trivy

Planned improvements:

* Lambda function and dynamoDB to store number of visits to the site
* CI/CD pipeline for automatic deployment and testing on PR Merge if the relevant files have been modified
* Improvements to the site content to differentiate it from my LinkedIn
* Infrastructure as code for all AWS resources used
* Architecture diagram

## Credits

* [astro-theme-resume](https://github.com/srleom/astro-theme-resume) for the astro template I used to create the website
