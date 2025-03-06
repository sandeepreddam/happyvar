pipeline {
    agent any
    stages {
        stage('Check Environment') {
            steps {
                sh ' echo "MAVEN_HOME: $MAVEN_HOME" && echo "PATH: $PATH" && mvn -version'
            }
        }
    }
}
