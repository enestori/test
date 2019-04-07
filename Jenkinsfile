node {
  stage ('Checkout') {
    git 'https://github.com/enestori/test/'
    stage 'Build'
    sh 'make all'
    stage 'Test'
    sh 'make test'
  }
}

