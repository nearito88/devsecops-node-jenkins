pipeline {
  agent any

  tools {
    nodejs 'node20'
  }

  stages {
    stage('Install') {
      steps {
        dir('app') {
          sh 'npm install'
        }
      }
    }

    stage('Test') {
      steps {
        dir('app') {
          sh 'npm test'
        }
      }
    }
    
    stage('SonarQube Scan') {
      steps {
        withSonarQubeEnv('sonarqube') {
          sh 'sonar-scanner'
        }
      }
    }
  }
}
