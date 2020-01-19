node{
     stage('SCM Checkout'){
     git 'https://github.com/erpky88/Healthcare'
    }
     stage('Compile-Package'){
     // GET MAVEN HOME PATH 
      def mvn_version = 'M3'
      withEnv( ["PATH+MAVEN=${tool mvn_version}/bin"] ) {
       //sh "mvn clean package"
}
     def mvnHOME = tool name: '', type: 'maven'
     sh "${mvnHOME}/bin/mvn package"          
   }
  }
         
