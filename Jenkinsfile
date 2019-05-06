pipeline {
    agent {
        label 'ruby-test'
    }

    stages {
        stage('Build') {
            steps {
                sh "ruby test.rb"
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
