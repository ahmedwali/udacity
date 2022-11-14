## [ Project Submission ]

## Screenshots

- The S3 bucket is visible in the AWS Management console

  ![](./s3-bucket.png)

- All the website files uploaded to the newly created S3 bucket

  ![](./uploaded-files.png)

- The bucket should allow public access. The S3 bucket has an IAM bucket policy that makes the bucket contents publicly accessible

  ![](./s3-policy.png)

- The S3 bucket is configured to support static website hosting

  ![](./s3-static-site.png)

- CloudFront has been configured to retrieve and distribute website files

  ![](./distribution.png)

## URLs

| Source                  | Link                                                                  |
| ----------------------- | --------------------------------------------------------------------- |
| CloudFront Distribution | https://d22xvem2wiu703.cloudfront.net                                 |
| S3 Website Endpoint     | http://website-eg-fwd-453080366549.s3-website-us-east-1.amazonaws.com |
