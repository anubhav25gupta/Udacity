pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') { 
            steps { 
                echo 'make' 
            }
        }
        stage('Test'){
            steps {
                
                input('Do you want to proceed') 
            }
        }
        stage('Deploy') {
            steps {
                echo 'Anubhav publish'
            }
        }
    }
}
