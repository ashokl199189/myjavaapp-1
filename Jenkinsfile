pipeline{
    agent any
    stages{
        stage("checkout"){
            steps{
                script{
                    sh "git clone https://github.com/mohandevops1869/myjavaapp-mohan.git"
                }
            }
        }
         stage("build code"){
            steps{
                script{
                    sh """
                    cd myjavaapp-mohan
                    mvn cleanpackage
                    """
                }
            }
         }
    }
}
