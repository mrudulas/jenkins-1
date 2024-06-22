pipeline {
    agent {
        label "AGENT1"
    }
    stages {
        stage('Build') { 
            steps {
               sh 'echo my build' 
            }
        }
        stage('Test') { 
            steps {
                             sh 'echo my test' 

            }
        }
        stage('Deploy') { 
            steps {
                             sh 'echo my deploy' 

            }
        }
    }
}