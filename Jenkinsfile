pipeline {
    agent any    
    stages {
        parallel {
            stage('stage1') {
                steps {
                    script {
                        	sh "echo 'stage 1'"
                    }
                }
            }
            stage('stage2') {
                steps {
                    script {
                        	sh "echo 'stage 2'"
                    }
                }
            }                
        }

    }
}
