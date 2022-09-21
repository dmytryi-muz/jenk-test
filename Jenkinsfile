pipeline {
    triggers {
        pollSCM('* * * * *')
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
