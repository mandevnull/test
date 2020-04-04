pipeline {
    agent { label 'aws' }
    stages {
      stage('Build & Test') {
        steps {
           sh 'echo hola > hola.txt'
           sh 'ls'
              }
      }
        stage ('check') {
            steps {
             sh 'ls'
            }
        }
    }
 }
