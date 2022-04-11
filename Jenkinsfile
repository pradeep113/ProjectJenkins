node{
	stage('Build'){
		echo"Building ..."
		echo "$BUILD_ID"
		/*archiveArtifacts artifacts: '**/target/*.jar', fingerprint: true*/
		}
	stage('Test'){
		echo"Testing..."
		/*junit '**/target/*.xml'*/
		}
	stage('Deploy'){
		echo"Deployinh..."
		}
	}
