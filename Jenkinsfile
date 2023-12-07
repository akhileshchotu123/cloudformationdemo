pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-infosys demos3 --template-body file://s3cft.json --region 'ap-south-1'"
              }
             }
            }
            }
