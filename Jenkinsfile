pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "🚀 Building PRODUCTION code from branch: ${env.BRANCH_NAME}"
            }
        }

        stage('Test') {
            steps {
                echo "✅ Running PRODUCTION tests on branch: ${env.BRANCH_NAME}"
            }
        }
    }
}
