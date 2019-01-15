node{
    stage('Checkout'){
        git credentialsId: 'github_key', url: 'https://github.com/github540/my-app'
        }
    stage('Compilie-Package'){
        //Get Maven Home path
        def mvnHome = tool name: 'maven-3', type: 'maven'
        sh "${mvnHome}/bin/mvn package"
        }
}
