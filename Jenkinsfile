pipeline {
    agent { docker { image 'hseeberger/scala-sbt' } }
    stages {
        stage('build') {
            steps {
                sh 'scala -version'
            }
        }
    }
}
