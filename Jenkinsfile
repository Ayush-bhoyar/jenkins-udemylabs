pipeline {
    agent any

    tools {
        go 'go-1.19'
    }

    stages {
        stage('Build') {
            steps {
                sh 'bash scripts/build.sh'
            }
        }

        stage('Test') {
            steps {
                sh 'bash scripts/test.sh'
            }
        }
    }
}
