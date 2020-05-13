pipeline {
   agent any
	
	environment {
    PATH = 'C:\\Program Files\\Git\\usr\\bin, ${env.PATH}'
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
