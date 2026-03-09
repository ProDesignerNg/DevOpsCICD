pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'echo "Build completed"'
            }
        }
    }

    post {
        success {
            echo 'Build finished successfully!'
        }

        failure {
            echo 'Build failed!'
        }

        always {
            echo 'Pipeline execution completed.'
        }
    }
}
