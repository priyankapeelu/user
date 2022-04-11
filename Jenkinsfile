pipeline {
   agent any

stages {

   //for each commit
   stage('lint checks') {
   steps {
   sh '''
     #~/node_modules/jslint/bin/jslint.js server.js
     echo link check
   '''
   }
  }
 } //End of stages
}