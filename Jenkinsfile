pipeline {
    agent any
    stages {
        stage('B-----clean-----') {
            steps {
                sh 'mvn clean'
            }
        }
        stage('------Test-------') {
            steps {
               sh 'mvn test'
            }
        }
        stage('----pakage----') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
