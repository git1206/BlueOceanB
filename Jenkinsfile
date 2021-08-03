pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        echo 'Hello Git'
      }
    }

    stage('Hello Girish') {
      steps {
        echo 'Hello World'
        input(message: 'Deploy to QA?', ok: 'Yes')
      }
    }

  }
}