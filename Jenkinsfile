
pipeline {
  agent any
  stages {
    stage('clone') {
      git branch: "branch1", url: "
    }
    stage('run') {
      steps{
           sh 'python3 app.py'
      }
    }
  }
}
