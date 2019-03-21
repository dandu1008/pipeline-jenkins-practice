pipeline{
    
    agent none
    
    options {
        timestamps() //its required timestamper plugin
    }
    
    stages {
        agent any
        options {
            skipDefaultCheckout()   
            }
        stage ('Build'){
            steps{
                echo "Hello World in Build"
            }
        }
        
        stage ('Test'){
            steps{
                echo "Hello World in Test"
            }
        }
    }
}
