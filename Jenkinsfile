pipeline{
    agent any
    stages{
        stage('checkout'){
            steps{
                script{
                    sh "git clone https://github.com/mohandevops1869/myjavaapp-mohan.git"
                }
            }
        }
        stage('build code'){
            steps{
                script{
                    sh """
                    ls -lrt
                    cd myjavaapp-mohan
                    """
                }
            }
        }
        stage('run unit test'){
            stapes{
                script{
                    sh """
                    cd myjavaapp-mohan
                    mvn test 
                    """
                }
            }
        }    
     
     
    }
        
}
