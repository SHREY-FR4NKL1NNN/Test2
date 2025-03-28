pipeline{
    agent any
    stages{

        stage('Checkout'){
            steps{
                git url: 'https://github.com/SHREY-FR4NKL1NNN/Test2.git', branch: 'master'
            }
        }
        stage('Build'){
            steps{
                echo 'Building the application'
            }
        }

        stage('Test'){
            steps{
                echo 'Testing the application'
            }
        }

        stage('Deploy'){
            steps{
                echo 'Deploying the application'
            }
        }
    }
}
