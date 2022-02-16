pipeline {
    agent any
    stages {
         stage('git clone') {
            steps {
                git 'https://github.com/letuanht/hello-world-java.git'
            }
        }
        stage('Test') {
            steps {
               echo "Testing completed"
            }
        }
        stage('Build') {
            steps {
               echo "Build completed"
            }
        }
    }
}
