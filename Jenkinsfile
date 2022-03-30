pipeline {
  agent any
  stages {
     stage('build') {
       steps {
         bat 'npm install'
         bat 'npm --version'
         bat 'C:\\Users\\HP\\AppData\\Roaming\\npm\\pm2 start app.js'
        }
      }
    }
  }
