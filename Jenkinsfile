pipeline{

	agent any
	stages {
	       stage('Build') {

			steps {
				sh 'kubectl apply -f manifest.yaml'
			}
	       }
	}
}

