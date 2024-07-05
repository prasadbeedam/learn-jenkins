pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo 'hello all' 
            }
        }
        stage('Test') { 
            steps {
                sh 'lscpu' 
            }
        }
        stage('Deploy') { 
            steps {
                sh 'lsmem' 
            }
        }
    }
}