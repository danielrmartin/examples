pipeline{
agent{label 'bazel'}
stages{
stage ('build'){
steps{
  container('bazel'){
  sh 'cd java-maven;bazel build //:java-maven'
  }//close container
  }//close step
  }//close stage
  }//close stages
  }//close pipeline
