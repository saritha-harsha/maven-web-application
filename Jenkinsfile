pipeline {
  agent any
stages{
  stage('gitcheckoutcode'){
  steps{
git branch: 'development', credentialsId: '22915043-138f-46e5-95e9-fc83c0c6ed16', url: 'https://github.com/saritha-harsha/maven-web-application.git'
  }
  }
  stage('mavenbuild'){
    steps{
      sh "mvn clean package"
    }
  }
}// for stages
} // for pipeline
