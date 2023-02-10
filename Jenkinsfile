pipeline {
    agent any
    tools {
        maven 'Buntua'
    }
    stages {
        stage ('Build') {
            steps {
                sh 'cd /MywebApp && mvn clean package'
            }
        }
    }
}