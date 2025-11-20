pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/<your-username>/<your-repo>.git'
            }
        }

        stage('Compile') {
            steps {
                sh 'javac hello_world.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java hello_world'
            }
        }
    }
}
