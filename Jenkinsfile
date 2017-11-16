pipeline {
  agent any
  stages {
    stage('Maven Release') {
      steps {
        mavenPipeline(gitCloneUrl: 'git@github.com:jstrachan/test-fabric8-declarative-step-functions-library.git', containerName: 'maven-3.6')
      }
    }
  }
}