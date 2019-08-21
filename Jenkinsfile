pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "netstat"
		        bat label: 'netstat', script: 'netstat.bat'
            }
        }
    }
}