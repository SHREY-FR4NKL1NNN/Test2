pipeline{
    agent any
    tools{
        maven 'demo'
    }
    stages {
        stage('Build'){
            steps{
                bat 'mvn clean package'
            }
        }
        stage('Test'){
            steps {
                bat 'mvn test'
            }
        }
    }
}
