node {
  stage('Git repo')
  {
 git 'https://github.com/22velu/mavenproject.git'   
  }
  stage('package')
  {
    bat 'mvn package'
  }
  stage('install')
  {
    bat 'mvn install'
  }
}
