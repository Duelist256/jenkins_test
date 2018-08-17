pipeline {
    agent { docker { image 'hseeberger/scala-sbt' } }
    stages {
        stage('build') {
            steps {
                bat 'scala -version'
            }
        }
    }
}