node{
  stage('Checkout Git'){
     
     git 'https://github.com/javahometech/myweb/'


     }


  stage('MvN Build'){


   sh 'mvn package'
   

    }

 stage('Deployment')
 
  sh 'java -jar /var/lib/jenkins/workspace/pipeline_demo01/target'

}


