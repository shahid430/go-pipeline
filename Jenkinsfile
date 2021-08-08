pipeline {
    agent any
    environment {
        GO11MODULES='on'
	}
    tools {
        go 'go-1.16'
    }
    stages {
    	stage('Build') {
            steps {
	        sh 'go build'
	    }
        }
    }
}
