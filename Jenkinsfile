/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'chmod -x gradlew'
                sh './gradlew build'
            }
        }
    }
}