pipeline {
    agent any    
    stages {
        stage('first pipeline') {
            steps {
                script {
                    	sh "echo 'first pipeline'"
                }
            }
        }
        stage('Config') {
            timeout(60, unit: 'SECONDS') {
                input(message:'OK?', ok: 'done')
            }
        }
    }
}
