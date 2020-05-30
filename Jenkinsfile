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
        git merge qa -m "Esto es un merge con mensaje"
      }
    }
  }
}
