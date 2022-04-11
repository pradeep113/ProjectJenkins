node{
	stage('Build'){
		/*echo"Building ..."*/
		sh 'make'
		archiveArtifacts artifacts: '**/target/*.jar', fingerprint: true
		}
	stage('Test'){
		/*echo"Testing..."*/
		sh 'make check || true'
		junit '**/target/*.xml'
		}
	stage('Deploy'){
		echo"Deployinh..."
		}
	}
