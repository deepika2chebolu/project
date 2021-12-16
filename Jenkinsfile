pipeline {
    agent any

    stages {
        stage('code-validation') {
            steps {
                echo 'validate-code..'
                sh 'mvn validate compile'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
