# Lambda cli

## How to update the lambda code
  - step 1: COmpress the code into .zip format.
  - step 2: Execute below command
aws lambda update-function-code \
    --function-name  my-PublicSecurityGroupMonitor \
    --zip-file fileb://PublicSecurityGroupMonitor.zip --region us-west-2
