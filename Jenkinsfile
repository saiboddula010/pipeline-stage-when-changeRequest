pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				//changeRequest title:"when-pr"
				buildingTag()
			}
		
            steps {                
                echo 'Hello World changing request'
            }
        }
    }
}
