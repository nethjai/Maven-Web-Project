#!groovy

node (node1) {
	   
	stage('Checkout'){

          checkout scm
       }

       stage('BuildArtifact'){

         // sh 'mvn install'
	       
	       sh 'mvn clean'
       }
	   
      stage('Sonar') {
                    //add stage sonar
                   // sh 'mvn sonar:sonar'
                }
       
}
