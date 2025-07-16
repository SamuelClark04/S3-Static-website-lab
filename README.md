# S3 Static Website Hosting + Permissions Troubleshooting

## Project Description
This lab demonstrates how to deploy a fully functional static website using Amazon S3 — and how to troubleshoot and fix common permission and rendering issues.

I hosted a custom HTML page in an S3 bucket, configured public access, and simulated a real-world failure (403 Forbidden) by initially leaving permissions misconfigured.

## Key Skills Practiced
- S3 bucket setup
- Static website hosting
- Bucket policy configuration
- MIME type troubleshooting (`text/html')
- Web rendering validation
- Cloud monitoring readiness (logging setup)
- Lightweight front-end formatting (HTML/CSS)

## Tech Stack
- Amazon S3
- HTML / CSS
- CloudWatch (optional logging/monitoring)
- IAM / Bucket Policies

## Problem Simulated
Initially, the site rendered raw HTML as plain text. I traced the issue to:
- Improper content-type setting during file upload
- Misconfigured public access permissions

## Final Outcome
- Fully working hosted static site
- Responsive design with centered layout
- Can be used as a portfolio landing page or S3 resume page

---

**Live site** (http://sams-static-site-10101010101022.s3-website-us-east-1.amazonaws.com/):  
If you'd like to share your static S3 website, drop the public link here.
