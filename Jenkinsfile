
pipeline{
    agent any
    tools {
    maven 'maven'
    jdk 'jdk11'
}
    stages{
        stage('checkstyle'){
            steps{
				bat 'mvn --version'
				bat 'java --version'
  
             }
       
         }
      }
}
