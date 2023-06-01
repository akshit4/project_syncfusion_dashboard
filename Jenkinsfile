pipeline{
  agent any
  
  stages{
    stage('build'){
      step{
        sh 'npm install'
      }
    }
    
    stage('source-code-import'){
      step{
        git branch: 'main', changelog: false, poll: false, url: 'https://github.com/akshit4/project_syncfusion_dashboard'
      }
    }
  }
}
