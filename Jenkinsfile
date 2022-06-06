// Work on this later

pipeline {
    agent any

    stages {
        stage ("Git Checkout") {
          steps {
            sh "git clone <link>"
            }
        }

		stage ("Docker Build") {
	        steps {
	            sh "mvn spring-boot:build-image"
                //do some tagging

            }
        }

        stage ("deploy") {
        	steps {
                //sh "docker run avaeroh/pi400:tagname"
            }
        }
    }

}