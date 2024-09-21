pipeline {
 agent any

 environment {
    BRANCH_NAME = 'main'
    GIT_URL = 'https://github.com/Darex001/awscicd.git'
    }
     

     stages {
        stage('build'){
            steps{
                sh 'echo build'
            }
        }
        stage('test'){
            steps{
                sh 'echo test'
            }
        }
        stage(code){
            steps{
                sh 'echo code'
            }
        }

     }


}