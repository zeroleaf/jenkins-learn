pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo \'Build\''
        sh '''echo "Multiline shell steps works too"
ls -lah'''
        timeout(time: 3) {
          sh 'echo "Time limit in 3 seconds"'
        }
        
      }
    }
  }
}