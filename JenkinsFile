pipeline{
 agent any
 parameters{
  choice(name: 'VERSION', choice:['1.1.0','1.2.0'], description: '')
  
 }
 stages{
 
   stage("build"){
    echo "Build on process ${params.VERSION}"
   }
   stage("test"){
    echo "Test on process"
   }
}
