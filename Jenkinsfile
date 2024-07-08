pipeline {
  agent any
  stages {
    stage('Linting Check') {
      steps {
        sh '''echo $(date)
echo "Starting the linting check"'''
      }
    }

    stage('Testing') {
      steps {
        sh 'echo "Testing the Project now"'
      }
    }

  }
}