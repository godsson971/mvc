pipeline {
agent any
stages{
  stage('Build'){
    steps{
    sh '/home/stagiaire/maven3/bin/mvn clean install'
    }
  }
  stage('Test'){
    steps{
    sh '/home/stagiaire/maven3/bin/mvn test'
    }
  }
}
}
