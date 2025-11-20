pipeline {
    agent any

    stages {
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
