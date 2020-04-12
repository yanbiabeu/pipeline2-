pipeline {
     agent any
  triggers { cron('*/1 * * * *') }
  stages {
    stage('Print the  hello') {
      steps {
        echo 'hello'
      }
    }
  }
}
