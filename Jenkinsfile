@Library("mylibs") _
pipeline {
  agent any
  tools {
    maven 'MAVEN'
    JDK 'java8'
  }
  stages{
    stage("Maven Build"){
      steps{
        sh "mvn clean package"
      }
    }
    
  }
}
