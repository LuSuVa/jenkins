pipeline {
  agent any
  tools {
    maven 'Maven 3.9.6'
  }  
  stages {
    stage ('checkout'){
      steps {
       git 'https://github.com/LuSuVa/lusuvair-back'
      }  
    } 
  }
}
