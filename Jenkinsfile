pipeline{
    agent any
    environment{
        NEW_VERSION =  '1.2.1'
    }
    
    stages{
        stage('BUILD_CODE'){
            steps{
                echo 'Building codes'
            }
        }
        
        stage('TESTING_CODE'){
            steps{
                echo 'Testing Code'
            }
        }
        stage('DEPLOY_QA){
            steps{
               echo 'Deploying code to QA'
            }
        }
    }
}
