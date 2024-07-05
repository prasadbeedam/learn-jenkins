pipeline {
    agent any

    stages {
        stage('one') {
            steps {
                 sh 'touch file1'
            }
        }
    }
    stages {
        stage('two') {
            steps {
                sh 'lscpu'
            }
        }
    }
}
