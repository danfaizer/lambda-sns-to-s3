## lambda-sns-to-s3
This is a dummy [AWS Lambda](https://aws.amazon.com/documentation/lambda/) function which stores received `event` data on a S3 bucket.

This is useful, for example, to store AWS SNS notifications that you may want to process later.

In order to test this lambda, modify `your-s3-bucket` with suitable values in `IAMRole.json` and `lambda.py` files, create the lamda in AWS, assign the role provided and you are done.
