node{
  stage('SCM CHECKOUT'){
    
    
    git 'https://github.com/lohith-tummala/FirstApp'
  }
  stage('Compile-Package'){
    def mvnHome = tool name: 'M3', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
    echo '${maven}'
  }
}
