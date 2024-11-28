pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        powershell run_build_script.ps1
      }
    }
    stage('Test') {
      steps {
       echo "Run tests" 
      }
    }
  }
}
