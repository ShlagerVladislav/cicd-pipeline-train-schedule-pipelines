pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automation'
        sh './gradlew build --no-daemin'
        archiveArtifacts articafts: 'dist/trainSchedule.zip'
      }
    }
  }
}
