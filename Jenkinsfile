pipeline {
    agent any

    stages {
        stage('SCM') {
            steps {
                echo 'Hello World'
                git branch: 'main', url: 'https://github.com/MadhanJK/my-node-app'
            }
        }
    stage('Test') {
            steps {
                echo 'Test is running'
            }
        }
    }
}

