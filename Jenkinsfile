pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				tag "2.*"
			}
		
            steps {                
                echo 'Hello World building tag'
            }
        }
    }
}
