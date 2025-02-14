pipeline {
  agent any

  stages {

    stage('checkout') {
      steps {
        sh 'git clone https://github.com/ksreddy117/Test.git'
      }
    }
    
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
