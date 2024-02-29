pipeline {
    agent {
        label 'MyNode'
    }
    
    stages{
        stage('Checkout') {
            steps {
                git "https://github.com/Gopala-Polimetla/DevOpsClassCodes.git"
            }
        }
        stage('Compile') {
            steps {
                sh "mvn compile"
            }
        }
    }
}
