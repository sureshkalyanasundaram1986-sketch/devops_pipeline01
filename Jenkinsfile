node{
  stage('Checkout Git'){
     
     git 'https://github.com/sureshkalyanasundaram1986-sketch/devops_pipeline01'


     }


  stage('MVN Build'){


   sh 'mvn package'
   

    }

 stage('Deployment')
 
  sh 'java -jar /var/lib/jenkins/workspace/pipeline_demo01/target'

}


