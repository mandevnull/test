pipeline {
    agent none
    stages {
      stage('Build & Test') {  agent { label aws }
        steps {
           sh 'echo hola > hola.txt'
           sh 'ls'
              }
      }
        stage ('check') {   agent { label aws2 }
            steps {
             sh 'ls'
            }
        }
    }
 }
