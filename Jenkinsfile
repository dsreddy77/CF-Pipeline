pipeline {
  agent any
   stages {
	stage('Clone Repo') {
	 steps {
	sh "export AWS_DEFAULT_REGION=us-east-1"
	sh "aws cloudformation create-stack --stack-name myteststack --template-body file://S3BucketCF.json --region 'us-east-1'"
					}
				}
		}
	}

