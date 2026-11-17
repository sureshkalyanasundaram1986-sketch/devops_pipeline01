node {

    stage('Checkout Git') {
        git branch: 'main',
            url: 'https://github.com/sureshkalyanasundaram1986-sketch/devops_pipeline01.git'
    }

    stage('Build') {
        sh 'mvn --version'
        sh 'mvn clean package'
    }
}
