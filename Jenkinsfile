node{
  stage('  CheckOut  '){
    git branch: 'master',
     url: 'git@github.com:deba1928/jenkins-tutorial.git'
  }
  stage('  Maven Clean  '){
    bat 'mvn clean'
  }
  stage('  Maven Build  '){
    bat 'mvn package'
  }
  
}
