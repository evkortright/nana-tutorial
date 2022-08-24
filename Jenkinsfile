pipeline {
 agent any

 stages {

  stage("build") {
   steps {
    echo 'building the application ...'
    cd
    ls
   }
  }

  stage("test") {
   steps {
    echo 'testing the application ...'
   }
  }

  stage("deploy") {
   steps {
    echo 'deploying the application ...'    
   }
  }
 }

 post {
  always {
   echo 'post always ...'
  }

  failure {
   echo 'post failure ...'
  }
 }
}
