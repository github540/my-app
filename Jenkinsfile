node{
    stage ('SCM checkout'){
        git 'https://github.com/github540/my-app'
    }
    stage ('Compile-Package'){
      def mvnHome = tool name: 'M3', type: 'maven'
        sh "${mvnHome}/bin/mvn package"
    }
 } 
     
