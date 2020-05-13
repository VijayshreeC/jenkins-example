pipeline {
   agent any
	
	environment {
    PATH = "C:\Users\\VijayshreeC\\AppData\\Local\\Programs\\Git\\bin";
   tools {
      // Install the Maven version configured as "M3" and add it to the path.
      maven "maven_3_5_0"
	}
	}
   stages {
		stage ('Initialize') {
		environment {
		PATH = "C:\Users\\VijayshreeC\\AppData\\Local\\Programs\\Git\\bin";
		}
            steps {
                sh '''
                    echo "PATH = ${PATH}"
                    echo "M2_HOME = ${M2_HOME}"
					
                ''' 
            }
        }
   }
}	
