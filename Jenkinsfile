pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                sh "echo 'Hello World 1'"
		sh "ls -al"
		bat "'C:/Program Files/Java/jdk1.8.0_191/bin/javac.exe' HelloWorld.java"
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