pipeline {
    agent {
        label 'MyNode'
    }
    
    stages{
        stage('Compile') {
            steps {
                sh "mvn compile"
            }
        }
    }
}
