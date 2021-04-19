node {

  def busybox = docker.image('busybox:latest')
  stage('Prepare') {
    echo 'ABC...'
  }

  stage('Ready') {
    busybox.inside {
      sh "echo Hello from within!"
    }
  }
}
