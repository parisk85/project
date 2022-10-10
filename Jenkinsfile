/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'openjdk:17-alpine' } }
    stages {
        stage('build') {
            steps {
                sh './gradlew build'
            }
        }
    }
}