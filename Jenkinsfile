/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                bat 'cd $WORKSPACE/my-project && npm install'
                bat 'set'
                bat 'echo hello'
            }
        }
    }
}
