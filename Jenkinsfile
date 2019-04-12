node{
  stage( 'SCM Checkout '){

   } 
    git 'https://github.com/topgun93/spring-project'
    }
    stage('Compile-Package'){
    dev mvnHOME =  tool name: 'maven', type: 'maven'
        sh "${mvnHOME}/bin/mvn package"
    }
   } 
