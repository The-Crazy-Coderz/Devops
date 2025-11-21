pipeline {
    agent any

    stages {

        stage('Webhook Triggered') {
            steps {
                echo "🎯 Webhook Received!"
                echo "Branch: ${env.GIT_BRANCH}"
                echo "Commit ID: ${env.GIT_COMMIT}"
                echo "Triggered by: ${env.GIT_AUTHOR_NAME}"
                echo "Commit Message: ${env.GIT_COMMIT_MESSAGE}"
            }
        }

        stage('Build') {
            steps {
                echo '🚧 Building the project...'
            }
        }

        stage('Test') {
            steps {
                echo '🧪 Running Tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo '🚀 Deploying...'
            }
        }
    }
}
