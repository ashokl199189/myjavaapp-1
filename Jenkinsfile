pipeline {
    agent any
    stages {
        stage("checkout"){
            steps {
                git "https://github.com/ashokl199189/myjavaapp-1.git"
            }
        }
        stage("build stage"){
            steps {
                sh "mvn clean install"
            }
        }
    }
}