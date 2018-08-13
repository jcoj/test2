pipeline {
	agent any
	triggers{
		pollSCM('* * * * *')
        }
	stages {
	  	stage("Checkout"){
 			steps {
		 		git url 'https://github.com/beerkeeper/python-ip-script.git'
			}
   
		}
        }
}
