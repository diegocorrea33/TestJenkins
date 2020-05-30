pipeline {
  agent any
  stages {
    stage('myStage'){
      steps {
        sh 'ls -la' 
      }
    }
    stage('Build') {
      steps { 
        sh 'ls'
        sh 'git checkout dev'
        sh 'git merge master'
        sh 'git push origin dev'
      }
    }
  }
}
