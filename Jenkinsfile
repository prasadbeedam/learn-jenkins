// pipeline {
//     agent {
//         label 'AGENT-1'
//     }
//     parameters {
//         string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
//         text(name: 'BIOGRAPHY', defaultValue: '', description: 'Enter some information about the person')
//         booleanParam(name: 'TOGGLE', defaultValue: true, description: 'Toggle this value')
//         choice(name: 'CHOICE', choices: ['One', 'Two', 'Three'], description: 'Pick something')
//         password(name: 'PASSWORD', defaultValue: 'SECRET', description: 'Enter a password')
//     }
//     options {
//         // Timeout counter starts AFTER agent is allocated
//         timeout(time: 1, unit: 'SECONDS')
//         disableConcurrentBuilds()
//     }
//     stages {
//         stage('Build') { 
//             steps {
//                 sh 'echo this is build' 
//             }
//         }
//         stage('Test') { 
//             steps {
//                 sh 'echo this is test' 
//             }
//         }
//         stage('Deploy') { 
//             steps {
//                sh 'echo this is deploy'
//             }
//         }
//     }
// }

pipeline {
    agent {
        label 'AGENT-1'
    }
    options{
        timeout(time: 30, unit: MINUTES)
    }
    environment{
        Greeting = 'hello-world'
    }
    perameters{
        //
    }
    stages{
        stage('build'){
            steps {
                sh 'echo this is build'
            }
        }
        stage('test'){
            steps {
                sh 'echo this is test'
            }
        }
    }
}