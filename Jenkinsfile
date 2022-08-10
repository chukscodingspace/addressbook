pipeline {
   agent {  label 'JenkinsNode' }
    stages {
        stage ('compilation') {
            steps {
                sh 'mvn -B compile'
            }
        }
        stage ('test') {
            steps {
                sh 'mvn -B test'
            }
        }
        stage ('package') {
            steps {
                sh 'mvn -B package'
            }
        }
     

    }
}
