pipeline{
  
  agent any
  tools{
    maven "maven-test-3.6"
  }
  
  stages{
    
    stage("build"){ 
      steps{
        echo 'bild test runing'
        cd 'demo'
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
