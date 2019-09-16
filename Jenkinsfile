pipeline {
  agent any
  stage('Build') {
    steps {
      echo 'runnning build automaation'
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'
    }
  }
}
