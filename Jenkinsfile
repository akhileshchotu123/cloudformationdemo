pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-cyient-3 --template-body file://s3cft.json --region 'us-east-1'"
              }
             }
            }
            }
