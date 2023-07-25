pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Replace this with the actual build commands for your project
                sh 'echo "Building the project..."'
            }
        }

        stage('Deploy') {
            steps {
                // Replace this with the actual deployment commands for your project
                sh 'echo "Deploying the project..."'
            }
        }
    }

    post {
        success {
            // This block will be executed if the pipeline succeeds
            echo 'Pipeline succeeded! Yay!'
        }

        failure {
            // This block will be executed if the pipeline fails
            echo 'Pipeline failed. Oops!'
        }

        always {
            // This block will always be executed, regardless of the pipeline result
            echo 'Pipeline execution complete.'
        }
    }
}
