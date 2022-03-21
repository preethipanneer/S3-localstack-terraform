# S3-localstack-terraform

Run 'docker-compose up' to spin up the s3 service in localstack container.
Run 'http://localhost:4566/health' in your browser to check if S3 service is running
Run 'terraform init' in a seperate bash to initial the aws provider.
Run 'terraform apply' to create a new s3 bucket and to add a text file in it.
Run 'aws --endpoint-url=http://localhost:4566 s3 ls s3://test-bucket' to verify  if the text file is added in the newly created s3 bucket


Note: Have docker, terraform and AWS cli installed before running all the commands above.
