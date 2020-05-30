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
        git merge experimental -m "Esto es un merge con mensaje"
      }
    }
  }
}
