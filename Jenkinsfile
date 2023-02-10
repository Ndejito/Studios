pipeline {
    agent any
    tools {
        maven 'Maven'
    }
    stages {
        stage ('Build') {
            steps {
                sh 'cd /MywebApp && mvn clean package'
            }
        }
    }
}