pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/ZakFormTP/jenkins-helloworld.git'
            }
        }

        stage('Build') {
            steps {
                sh 'javac Main.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Main'
            }
        }
    }
}
