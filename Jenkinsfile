pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo '123123'
      }
    }

    stage('tews') {
      steps {
        fingerprint(targets: '11', caseSensitive: true, defaultExcludes: true)
      }
    }

  }
}