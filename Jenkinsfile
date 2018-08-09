pipeline {
    agent any
    stages {
        stage('Deploy app (mock)') {
            steps {
                sh "echo 'building SUT....'"
                sh "sleep 10"
                sh "echo 'deploying SUT....'"
                sh "sleep 10"
            }
    stage('Deploy app (test)') {
             steps {
                  sh "mvn clean verify'"
                  }

        }
    }
}

