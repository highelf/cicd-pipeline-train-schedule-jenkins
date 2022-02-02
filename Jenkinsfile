pipeline {
  agent any
  stages{
    stage('Build'){
      steps{
        ehco 'This is the build step'
        sh './gradlaw build --no-deamon'
        archiveArtifacts artifact: 'src/trainSchedule.zip'
      }
    }
  }
}
