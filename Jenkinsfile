pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo "Building automation "
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts 'dist/trainSchedule.zip'
        }
      }
  } }
