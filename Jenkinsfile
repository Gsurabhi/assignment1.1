#!groovy

//1
stage 'clone_AssignmentProject'
node {
git 'https://github.com/BitwiseInc/assignment1.1.git'
}

//2
stage 'Clean'
node{
  //sh 'chmod +x gradlew'
  sh 'gradle clean --info' 
}

stage 'Unit Test'
node{
  sh 'gradle test --info' 
}
