pipeline {
 agent any
  stages {
     stage ("mvn Build") {
      steps {
       sh  "mvn clean install"
      }
      stage("create docker image"){
       steps {
       sh  "mvn clean install"
      }
     }
  }
 
}
