pipeline{
agent any
  stages {
    stage ('Build') {
      steps {
        echo " Running build automation"
        sh './gradlew build --no-demaon'
        arciveArtifacts artifacts: 'dist/tarinSchedule.zip'
      }
    }
  }
}
