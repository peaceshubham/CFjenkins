pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name ec2jenkins --template-body file://ec2.json --region 'ap-south-1'"
              }
             }
            }
            }
