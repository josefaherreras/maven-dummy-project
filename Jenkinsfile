 
pipeline {

  agent any

  tools {
    
    maven "jenkins-maven"

  }

  stages { 

    stage('TEST1'){

      steps {
        sh 'mvn clean install compile test'
      }
     
    }
  }
 
}
