pipeline {
  agent any
  environment {
    registry = "uday kumar ${BUILD_Number}"
  }
  stages {
    stage('moving to diff folder') {
      steps {
        sh "echo ${registry}"
      }
    }

  }
}
