pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'docker build -t test:v1 .'
            }
        }
    }
}
