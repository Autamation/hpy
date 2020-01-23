node{
 stage('SCM Checkout'){
git 'https://github.com/Autamation/hpy.git'
}
stage('Compile-Package'){
   def mvnHome = tool name: 'M2-HOME', type: 'maven'
      sh "${mvnHome}/bin/mvn package"
 sh 'mvn package'
}
}
