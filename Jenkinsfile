pipeline {
    agent any

    environment {
        APP_NAME = "jenkinsfile-pipeline-project"
    }

    stages {

        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Verify Python') {
            steps {
                sh 'python3 --version'
            }
        }

        stage('Run Application') {
            steps {
                echo "Running ${APP_NAME}..."
                sh 'python3 pipeline.py'
            }
        }

    }

    post {
        success {
            echo 'Pipeline completed successfully.'
        }

        failure {
            echo 'Pipeline failed.'
        }

        always {
            cleanWs()
        }
    }
}
