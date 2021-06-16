pipeline{
   agent any
  stages {
    stage ('Build'){
      steps {
        echo ''Running build autoamtion'
        sh './gradlew build --no-daemon'
        archieveArtifacts artifacts: "dist/trainSchedule.zip"
      }
    }
  }
}
