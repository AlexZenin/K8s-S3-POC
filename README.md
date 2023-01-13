# K8s-S3-POC

Proof of concept for using path based filtering with a K8s ingress controller and static site on S3

## Ingredients:

#### A simple static site hosted on S3.

Enabling static website hosting provides a specific `http://<bucket-name>.s3-website-<region>.amazonaws.com` endpoint for the bucket.

https://docs.aws.amazon.com/AmazonS3/latest/userguide/WebsiteAccessPermissionsReqd.html

[Hosting multiple sites in S3](https://karen-kua.medium.com/how-to-host-multiple-react-apps-in-the-same-aws-s3-bucket-cloudfront-c518c2b38408)
