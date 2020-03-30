plugins{
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automation'
        sh './gradlew build --no-daemon'
        archiveartifacts artifiacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
