pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                sh "echo 'Hello World 1'"
		sh "ls -al"
		sh "whoami"
            }
        }
        stage('--test--') {
            steps {
                sh "echo 'Hello World 2'"
		sh "ls -al"
		sh "java HelloWorld"
            }
        }
        stage('--package--') {
            steps {
                 sh "echo 'HelloWorld executed'"
            }
        }
    }
}