//para pruebas de qabot, asociado al repo gitlab test-qabot
node('slave-xb') {
	deleteDir()
	checkout scm
	stage("run") {
	    sh "chmod ugo+x main-script.sh"
	    sh "./main-script.sh"
	}
}