pipeline {
    agent any

    stages {
        stage('Unittest') {
            steps {
                echo "testing"
            }
        }
        stage('Lint') {
            steps {
                echo "linting"
            }
        }
        stage('Functional test') {
            steps {
                echo "testing"
            }
        }
    }

post {
    always {
        junit allowEmptyResults: true, testResults: 'results.xml'
    }
}

}
