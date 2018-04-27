pipeline {
  agent any
  stages {
    stage('') {
      steps {
        sh 'sleep 5'
        echo 'adfsadf'
        timeout(time: 3, activity: true) {
          build(job: '123', quietPeriod: 2)
        }

      }
    }
  }
}