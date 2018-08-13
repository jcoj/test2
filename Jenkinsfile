pipeline {

	agent any
	triggers {
		pollSCM('* * * * *')
        }

	stages {
	  	stage("Checkout"){
 			steps {
		 		git url:  'https://github.com/beerkeeper/python-ip-script.git'
			}
   
		}
		stage("Running the python app"){
			steps {
				sh "/usr/bin/python main.py"

			}
               }
       }
}
