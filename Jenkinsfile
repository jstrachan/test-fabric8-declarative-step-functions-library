@Library('github.com/fabric8io/fabric8-declarative-pipeline-step-functions-library@master')

def ignoreCompileError

echo "Lets try the mavenPipeline"

pipeline {
  agent any
  stages {
    stage('Release') {
      steps {
        mavenPipeline {
        }
      }
    }
  }
}
