pipeline{
agent{label 'bazel'}
stages{
stage ('build'){
  dir('java-maven'){
steps{
  container('bazel'){
  sh 'bazel build //:java-maven'
  }//close container
  }//close dir
  }close step
  }//close stage
  }//close stages
  }//close pipeline
