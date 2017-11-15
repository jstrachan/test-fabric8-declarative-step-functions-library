pipeline {
  agent any
  stages {
    stage('Maven Release') {
      steps {
        mavenPipeline project: "Cheese", foo: "bar"
      }
    }
  }
}
