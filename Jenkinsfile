pipeline{
  agent any
  
  stages{
    stage('build'){
      sh 'npm install'
    }
    
    stage('source-code-import'){
      git branch: 'main', changelog: false, poll: false, url: 'https://github.com/akshit4/project_syncfusion_dashboard'
    }
  }
}
