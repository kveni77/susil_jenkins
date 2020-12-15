pipeline{
    agent any
     tools{
                maven 'mymaven'
                }
    
    stages{
        
        stage('checkout'){
            
               steps{
                
                git 'https://github.com/nsusil/my-app-master.git'
                }
        }
        
        stage('build'){
             
            
                
            steps{
               
                sh 'mvn clean package'
            }
        }
        
            
        stage('deploy'){
            
            steps{
               sh 'echo hello'
            }
        }
        
            
        
    }
    
    
    
}


