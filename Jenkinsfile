pipeline {
  agent any
  
  environment {
    build = "${currentBuild.number}"
    
    
    }
    stages {
      
      stage('Build'){
        steps{
          echo 'Build job Started first'
          script{
            def path = []
            paths = readJSON file: "Build_jsondata.json"
          
            echo "${paths.hello}"
            echo "${paths.country}"
            echo "${paths.build_BL_path}"
            echo "${paths.build_BL_file}"
        }
      }  
    }
  }  
}    
