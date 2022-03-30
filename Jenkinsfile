pipeline {
  agent any
  stages {
     stage('build') {
       steps {
         bat 'npm install'
         bat 'npm --version'
         bat 'pm2 start app.js'
        }
      }
    }
  }
