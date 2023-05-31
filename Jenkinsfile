 
pipeline {

  agent any

  tools {
    
    maven "jenkins-maven"

  }

  stages { 

    stage('TESTING'){

      steps {
        sh 'mvn clean install compile test'
      }
     
    }
  }
 
}
