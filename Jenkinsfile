// Just a comment
pipeline {

  agent any

  stages {

    stage("build-api") {

      steps {

        echo 'Preparing to build API'
        sh 'docker build api Dockerfile'

      }

    }
/*
    stage("build-ui") {

      steps {

        echo 'Preparing to build UI'
        sh 'docker build ui ui/Dockerfile'

      }

    }

    stage("test-api") {

      steps {

      }

    }

    stage("test-ui") {

      steps {

      }

    }
*/
    stage("deploy-api") {

      steps {

        echo 'Preparing to deploy API'

      }

    }
/*
    stage("deploy-ui") {

      steps {

        echo 'Preparing to deploy UI'

      }

    }
*/
  }

}
