pipeline {
    agent any 
    options {
        timeout( time: 1, unit:'SECONDS')
    }
    stages {
        stage('Build') { 
            steps {
               sh 'echo my build 123 ' 
            }
        }
        stage('Test') { 
            steps {
                             sh 'echo my test 123' 
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