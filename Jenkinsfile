pipeline {
    agent any
    tools {
        maven 'Buntua'
    }
    stages {
        stage ('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}