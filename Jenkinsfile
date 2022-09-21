pipeline {
    triggers {
        pollSCM('H/3 * * * *')
    }
    agent any



    stages {
        stage('build') {
            steps {
                script {
			sh "echo build"
                }
            }
        }
    }
}
