node{
     stage'SCM Checkout'){
     
     git 'https://github.com/erpky88/Healthcare'
    }
     stage('Compile-Package'){
     // GET MAVEN HOME PATH     
     def mvnHOME = tool name: '', type: 'maven'
          sh "&{mvnHOME}/bin/mvn package"     
         
   }
  }
         
