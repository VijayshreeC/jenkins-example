pipeline {
   agent any
	
	environment {
    PATH = 'C:\\Users\\VijayshreeC\\AppData\\Local\\Programs\\Git\\bin, ${env.PATH}'
	}
   tools {
      maven "maven_3_5_0"
	}
	
   stages {
   
		stage ('Initialize') {
		environment {
		PATH = 'C:\\Users\\VijayshreeC\\AppData\\Local\\Programs\\Git\\usr\\bin, echo "${PATH}"'
		}
            steps {
                bat "mvn -Dmaven.test.failure.ignore=true clean package"
            }
        }
   }
}	
