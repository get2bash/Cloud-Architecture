step 1: created the diagram
step 2: created the network and parameter file with the scripts
step 3: deployed and created my stack (network) using = aws cloudformation create-stack --stack-name $ --template-body file://$  --parameters file://$ --capabilities "CAPABILITY_IAM" "CAPABILITY_NAMED_IAM" --region=us-east-1
step 4: created the servers and parameter file with the scripts
step 5: deployed and created my stack (server) using = aws cloudformation create-stack --stack-name $ --template-body file://$  --parameters file://$ --capabilities "CAPABILITY_IAM" "CAPABILITY_NAMED_IAM" --region=us-east-1
step 6: created an IAM role to give it access to S3 bucket
Url: http://proje-webap-mu620paws3fy-549097448.us-east-1.elb.amazonaws.com/