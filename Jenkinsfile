node{
 stage('SCM Checkout'){
git 'https://github.com/Autamation/hpy.git'
}
stage('Compile-Package'){
   def mvnHome = tool name: 'M2_HOME', type: 'maven'
      sh "${mvnHome}/bin/mvn package"
 sh 'mvn package'
}
}
