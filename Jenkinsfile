pipeline {
    agent any
    stages {
        stage('Check Environment') {
            steps {
                sh ' echo $MAVEN_HOME" && echo $PATH" && mvn -version'
            }
        }
    }
}
