pipeline {
    agent any
    stages {
        stage('Build') {
            steps { echo "🛠️ Building DEVELOPMENT code from ${env.BRANCH_NAME}" }
        }
        stage('Test') {
            steps { echo "⚡ Running DEVELOPMENT tests on ${env.BRANCH_NAME}" }
        }
    }
}
