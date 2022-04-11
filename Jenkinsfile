node{
	stage('Build'){
		/*echo"Building ..."*/
		archiveArtifacts artifacts: '**/target/*.jar', fingerprint: true
		}
	stage('Test'){
		/*echo"Testing..."*/
		junit '**/target/*.xml'
		}
	stage('Deploy'){
		echo"Deployinh..."
		}
	}
