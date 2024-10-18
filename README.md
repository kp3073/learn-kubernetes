# learn-kubernetes

# this how to AUTHENTICATE to ECR private repositories

kubectl create secret docker-registry aws-ecr --docker-server=471112727668.dkr.ecr.us-east-1.amazonaws.com
--docker-username=AWS --docker-password=$(aws ecr get-login-password)