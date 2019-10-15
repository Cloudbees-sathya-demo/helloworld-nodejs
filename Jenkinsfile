pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'print("test script")'
        node(label: 'test-node') {
          echo 'print("Test")'
        }

      }
    }
  }
}