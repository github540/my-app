node{
    stage('Checkout'){
        git credentialsId: 'github_key', url: 'https://github.com/github540/my-app'
        }
    stage('Compilie-Package'){
        sh label: '', script: 'mvn package'
        }
}
