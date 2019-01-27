node{
   stage('SCM Checkout'){
     git 'https://github.com/makr123/mvn-project.git'
   }
   stage('Compile-Package'){
    sh 'mvn package'
  }
}
