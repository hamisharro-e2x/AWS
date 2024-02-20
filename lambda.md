# Lambda

- Only pay for what you use (in terms of computing usage)
  - Cost is linked to invocations
- Execution Role must be assigned
  - IAM role for lambda
  - Sets permissions
  - The basic role allows lambda to publish logs to Cloudwatch
- Use the test to run Lambda manually
  - When testing you can provide a payload to be used
  - When lambda runs it will create a log stream, which will contain the logs…
- Runs code based on events (invoked by events):
  - Uploads to S3 bucket
  - Updates to DynamoDB
  - Data in Kinesis Streams
  - In-App activity
- Service handles scaling, capacity, and metrics.
- Code run on lambda is known as a lambda function.
  - Upload code through ZIP file
  - Use integrated developer environment in AWS console
  - Sample functions are provided
- It is easy to call other AWS services due to OOTB functionality.

| Resource                   | Link                                        |
| -------------------------- | ------------------------------------------- |
| Introduction to AWS Lambda | https://www.youtube.com/watch?v=eOBq__h4OJ4 |
