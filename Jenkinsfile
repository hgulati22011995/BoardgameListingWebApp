pipeline {
    agent any
    
    tools {
        maven 'maven3'
        jdk 'jdk-17'
    }

    stages {
        stage('Compile') {
            steps {
                sh 'mvn compile'
            }
        }
        
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
        
        stage('build') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
