pipeline {
  agent any
  
  environment {
    build = "${currentBuild.number}"
    bat " json build_jsondata.json"
    def props = readJSON text: '{ "key": "value" }'
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
      
