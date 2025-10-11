pipeline {
  agent any
    stages {
        stage('Install dependecies') {
            steps {
                bat 'npm install'
            }
        }
        stage('Test') {
            steps {
                bat 'npm test'
            }
        }
    }
}
