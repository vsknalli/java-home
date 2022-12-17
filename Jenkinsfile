@Library("mylibs") _
pipeline {
  agent any
  tools {
    maven 'MAVEN'
  }
  stages{
    stage("Maven Build"){
      steps{
        sh "mvn clean package"
      }
    }
    
  }
}
