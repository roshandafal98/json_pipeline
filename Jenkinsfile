pipeline {
  agent any
  
  environment {
    build = "${currentBuild.number}"
    def paths= readJSON file: "Build_jsondata.json"
    
    }
    stages {
      stage('Build'){
        steps{
          echo 'Build job Started first'
          
          echo "${paths.Build.first}"
        }
      }  
     stage('Deploy'){
      steps {
        echo 'Deploy Stage started'
        }
        }
    }
  }  
      
