pipeline{
  
  agent any
  tools{
    maven "maven-test-3.6"
  }
  
  stages{
    
    stage("build"){ 
      steps{
        echo 'bild test runing'
        sh 'mvn clean install'
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
}
