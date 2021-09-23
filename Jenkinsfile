pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
				sh 'echo "Hello World or something like that"'
				sh '''
					echo "Multiline shell steps works too"
				    ls -lah
				'''
            }
        }
    }
}