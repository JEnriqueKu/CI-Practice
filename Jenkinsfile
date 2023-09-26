/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'cd $WORKSPACE/my-project && npm install'
                sh 'set'
                sh 'echo hello'
            }
        }
    }
}
