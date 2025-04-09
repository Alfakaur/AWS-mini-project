 Project- AWS Static Website 

The project showcases how to host a simple static website using AWS S3 (Simple Storage Service).

 Project Description
In this project,  a HTML website is created & hosted on AWS S3 as a static website, making it cost-effective to deploy small projects.

Following are the steps performed for this Project

 1. Create an S3 Bucket on AWS console
   - Created an S3 bucket named `my-first-s3-site-2025` to host the website files.
   - Configured the bucket by enabling "Static website hosting" option in bucket settings.

2. Add Index HTML File
   - Created an 'index.html' file.
   - Added basic HTML content to display a heading and hello world text.

 3. Upload Files to S3
   - Uploaded the `index.html` file to the S3 bucket using the AWS CLI.
   - Altered bucket permissions to make the website publicly accessible.

4. Enable Public Access & Configure Permissions
   - Set the S3 bucket policy to allow public access for the index.html file.
   - Used AWS Identity and Access Management (IAM) to create a user with permissions to access the S3 bucket.

5. Access the Website via Endpoint
   - After uploading the `index.html` file, I used the S3 endpoint URL to access the website in the browser.

 Technologies Used:
- AWS - S3, IAM, CLI
- HTML - Basic static website content

 How to Run the Project:
1. Upload the `index.html` to an AWS S3 bucket.
2. Enable static website hosting in S3.
3. Access the website via the provided endpoint.
