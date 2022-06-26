#Setting up a Cloud architecture using CloudFormation


Created the Infrastructure diagram
Created the network and parameter file with the scripts
Deployed and created my stack (network) using = aws cloudformation create-stack --stack-name $ --template-body file://$  --parameters file://$ --capabilities "CAPABILITY_IAM" "CAPABILITY_NAMED_IAM" --region=us-east-1
Created the servers and parameter file with the scripts
Deployed and created my stack (server) using = aws cloudformation create-stack --stack-name $ --template-body file://$  --parameters file://$ --capabilities "CAPABILITY_IAM" "CAPABILITY_NAMED_IAM" --region=us-east-1
Created an IAM role to give it access to S3 bucket
Url: http://proje-webap-mu620paws3fy-549097448.us-east-1.elb.amazonaws.com/
