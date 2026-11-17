node {

    stage('Checkout Git') {

        git branch: 'main',
            url: 'https://github.com/sureshkalyanasundaram1986-sketch/devops_pipeline01.git'
    }

    stage('MVN Build') {

        sh 'mvn clean package'
    }

    stage('Deployment') {

        sh 'ls -l target'
        sh 'java -jar target/*.jar'
    }
}
