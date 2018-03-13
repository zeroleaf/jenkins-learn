pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo \'Build\''
        sh '''echo "Multiline shell steps works too"
ls -lah'''
      }
    }
  }
}