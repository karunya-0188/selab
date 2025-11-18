node{
  stage('Build'){
        echo 'started building...'
        bat 'mvn clean install'
    }
  stage('Test'){
    echo 'started testing...'
    bat 'mvn test'
  }
  stage('Deploy'){
    echo 'started Deploying...'
    bat 'echo deployment completed'
  }
  
}
