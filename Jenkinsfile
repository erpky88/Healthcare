node{
     stage('SCM Checkout'){
     git 'https://github.com/erpky88/Healthcare'
    }
     stage('Compile-Package'){
     // GET MAVEN HOME package
     def mvnHOME = tool name: '', type: 'maven'
     sh "${mvnHOME}/bin/mvn package"          
    }
   }
     

