pipeline{
	agent any
	stages{
		stage("Build"){
			steps{
				echo "Building ..."
			}
			post{
				success{
					mail to: "wendy.lam0602@gmail.com",
					subject: "Build Status Email",
					body: "Build was successful!"
				}
			}
		}
	}
}
