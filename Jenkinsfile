pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo "${workspace}"
                sh "ls"
                sh "cat app/app.js"
            }
        }
    }
}