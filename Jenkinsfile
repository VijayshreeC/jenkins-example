pipeline {
   agent any
	
	environment {
    PATH = 'C:\\Users\\VijayshreeC\\AppData\\Local\\Programs\\Git\usr\\bin, ${env.PATH}'
	}
   tools {
      maven "maven_3_5_0"
	}
	
   stages {
   
		stage ('Initialize') {
		
            steps {
                sh '''
                    echo "PATH = ${PATH}"
                    echo "M2_HOME = ${M2_HOME}"
					
                ''' 
            }
        }
   }
}	
