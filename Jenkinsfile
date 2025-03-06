pipeline {
    agent any
    environment {

        echo $MAVEN_HOME
        echo $MAVEN_PATH
   }
    stages {
        stage('Clone Repository') {
            steps {  
                sh 'git clone https://github.com/RavitejaAdepudi/javawar'
            }
        }
        stage('Build with Maven') {
            steps {
                sh 'mvn -f /var/lib/jenkins/workspace/happyvar/javawar/pom.xml install'
            }
        }
    }
}
