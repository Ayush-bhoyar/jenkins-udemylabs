pipeline {
    agent any
    tools { go 'go-1.19' } // Comes from the jenkins global config
    ...
stages {
        stage('Build') {
            steps {
                sh 'bash scripts/build.sh' // Run the build.sh asset
            }
        }
        stage('Test') {
            steps {
                sh 'bash scripts/test.sh' // Run the test.sh asset
            }
        }
    }
}


