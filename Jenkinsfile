pipeline {
  agent any
  environment {
    registry = "2.0.${BUILD_Number}"
  }
  stages {
    stage('moving to diff folder') {
      steps {
        bat "echo ${registry}"
      }
    }

  }
}
