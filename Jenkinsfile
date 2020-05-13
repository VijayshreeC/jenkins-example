pipeline {
   agent any
	
	environment {
    PATH = 'C:\\Users\\VijayshreeC\\AppData\\Local\\Programs\\Git\\bin, ${env.PATH}'
	}
   tools {
      maven "maven_3_5_0"
	}
	
   stages {
		pipeline {
   agent any
	
	environment {
    PATH = 'C:\\Users\\VijayshreeC\\AppData\\Local\\Programs\\Git\\bin, ${env.PATH}'
	}
   tools {
      maven "maven_3_5_0"
	}
	
   stages {
   
   
   stage('build') {
 
        checkout scm
        def v = version()
        currentBuild.displayName = "${env.BRANCH_NAME}-${v}-${env.BUILD_NUMBER}"
        mvn "clean verify"
    }
}
}
