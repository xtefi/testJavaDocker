pipeline{
  
  agent any
  
  stages{
    
    stage("build"){ 
      steps{
        mvn clean install
      }
    }
    
    stage("test"){
      steps{
        echo 'testing test'
      }
    }
    
    stage("deploy"){
      steps{
         echo 'testing deploy'
      }     
    }
  }
  
  post {
    always{
      
    }
    success{
      
    }
    failure{
      
    }
}
