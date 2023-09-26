/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'maven:3.9.4-eclipse-temurin-17-alpine' } }
    stages {
        stage('build') {
            steps {
                bat 'cd $WORKSPACE/my-project && npm install'
                bat 'set'
            }
        }
    }
}
