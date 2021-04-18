// Just a comment
pipeline {

  agent any

  stages {

    stage("checkout") {

      steps {

        echo 'Checking out repo'

        checkout([
          $class: 'GitSCM',
          branches: [[name: '*/main']],
          doGenerateSubmoduleConfigurations: false,
          extensions: [],
          submoduleCfg: [],
          userRemoteConfigs: [[url: 'https://github.com/ian-llewellyn/docktor']]
        ])

      }

    }

  }

}

/* The below is somehow equivalent to the pipeline {} and agent any lines above
node {
  // groovy script
}
*/
