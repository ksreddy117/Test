pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        echo 'Executing at Build Stage'
      }
    }
     stage('Test') {
       steps { 
         echo "Executing Test stage"
       }
     }
  }

  stage('Deploying') {
    steps {
      echo "Executing Deployment phase"
    }
  }
}
