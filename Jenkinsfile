pipeline {
	agent any
    stages {
        stage("Build"){
            steps {
                script {
                    currentBuild.displayName = "The name."
                    currentBuild.description = "The best description."
                }
            }
        }
        stage("Test"){
            steps {
                step{
					echo "Whatsupp"
				}
            }
        }
    }
}