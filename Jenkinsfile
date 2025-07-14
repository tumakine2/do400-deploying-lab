pipeline {
    agent {
        node {
            label 'maven'
        }
    }
    stages {
        stage('Unit tests') {
            steps {
                sh './mvnw verify'
            }
        }
    }
}