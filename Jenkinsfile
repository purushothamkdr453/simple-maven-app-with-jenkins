pipeline {
    agent {
       # restircting the job to run certain agents which matches the label
       # label 'agent1' 
       docker {
           image 'maven:3.3.3'
       }
    }
    stages {
        stage('checkout') {
            steps {
                sh 'mvn --version'
                sh 'sleep 10'
                sh 'echo Bye'
            }
        }
    }
}
