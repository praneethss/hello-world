pipeline {
    agent any

    stages {
        stage("clone code"){
            steps{
                git url: 'https://github.com/praneethss/hello-world.git'
            }
        }
        stage('Build') {
            steps {
                sh "mvn clean install"
            }
        }
    }
}
