pipeline{
    
    agent any
    
    options {
        timestamps() //its required timestamper plugin
    }
    
    stages {
        
        stage ('Build'){

            agent any

           // options {
           //     skipDefaultCheckout()   
           //}
            
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
