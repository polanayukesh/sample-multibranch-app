pipeline {
    agent any
    stages {
        stage('Build') {
            steps { echo "🌱 Building FEATURE branch code from ${env.BRANCH_NAME}" }
        }
        stage('Test') {
            steps { echo "🧪 Running FEATURE tests on ${env.BRANCH_NAME}" }
        }
    }
}
