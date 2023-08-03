pipeline {
 agent any

 stages{
  stage('hello'){
    step{
     echo "hello"
    }

  }

 stage('hi'){
   step{
   echo 'hi'
   bat 'dir'
   }
 }
 }

}