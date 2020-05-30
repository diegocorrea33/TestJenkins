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
        sh 'git checkout master'
        sh 'git merge qa'
        sh 'git push origin master'
      }
    }
  }
}
