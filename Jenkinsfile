node{
  stage('SCM CHECKOUT'){
    git 'https://github.com/lohith-tummala/FirstApp'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
}
