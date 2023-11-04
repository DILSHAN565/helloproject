pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git branch: 'main', credentialsId: 'git_credentials', url: 'https://github.com/DILSHAN565/helloproject.git'
            }
        }
    }
}
