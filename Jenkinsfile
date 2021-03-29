pipeline{
    agent any
    tools{
        jdk 'JDK_11'

    }
    stages{
        stage('Build'){
            steps{
                echo 'Hello World'
                sh 'java --version'
                //sh 'mvn --version'
                sh 'mvn clean compile' //istället för ovan
            }
        }
    }
}