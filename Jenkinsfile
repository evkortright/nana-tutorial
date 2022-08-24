pipeline {
 agent any

 stages {

  stage("build") {
   steps {
    echo 'building the application ...'
    sh "cd /Users/ekortright/courses/Painless_v8_4/src"
    sh "ls"
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
