pipeline {
    agent any 
    
    stages {
        stage('one') {
            steps {
                sh 'touch file1'
            }
        }
        stage('two') {
            steps {
                sh 'lscpu'
            }    
        }
    }
}
