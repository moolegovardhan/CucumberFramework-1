node{
   stage('SCM Checkout'){
     git 'https://github.com/moolegovardhan/CucumberFramework-1'
   }
   stage('Compile-Package'){
      // Get maven home path
      def mvnHome =  tool name: 'Maven', type: 'maven'   
      bat "${mvnHome}/bin/mvn package"
   }
   
}
