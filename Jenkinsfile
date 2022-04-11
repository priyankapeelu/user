pipeline {
   agent any

stages {

   //for each commit
   stage('lint checks') {
   steps {
     script {
      nodejs.lintChecks()
   }
  }
 } //End of stages
}
}