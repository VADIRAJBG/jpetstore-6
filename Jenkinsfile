pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                withMaven(Maven : 'maven'){
               sh 'maven clean'
                }
            }
        }
        
    }
}
