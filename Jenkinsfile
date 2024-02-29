pipeline {
    agent {
        label 'MyNode'
    }
    
    stages{
        stage('Verify') {
            steps {
                sh "ls -la"
            }
        }
        stage('Compile') {
            steps {
                sh "mvn compile"
            }
        }
        
    }
}
