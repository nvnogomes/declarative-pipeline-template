pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        powershell 'run_build_script.sh'
      }
    }
    stage('Test') {
      steps {
       echo "Run tests" 
      }
    }
  }
}
