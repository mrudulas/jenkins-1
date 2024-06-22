pipeline {
    agent any 
    options {
        timeout( time: 1, unit:'MINUTES')
    }
    stages {
        stage('Build') { 
            steps {
               sh 'echo my build fdfsdfk ' 
            }
        }
        stage('Test') { 
            steps {
                             sh 'echo mynnn test 123' 
                             sh 'slee 10'

            }
        }
        stage('Deploy') { 
            steps {
                             sh 'echo my deploy' 

            }
        }
    }
}