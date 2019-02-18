node{
  stage('SCM CHECKOUT'){
    tool name: 'M3', type: 'maven'
    git 'https://github.com/lohith-tummala/FirstApp'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
}
