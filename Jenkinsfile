pipeline {
    agent any
    stages {
        stage('Node Version') {
            steps {
                script {
                    def nodeHome = tool name: 'Node', type: 'NodeJS'
                    env.PATH = "${nodeHome}/bin:${env.PATH}"
                    sh 'node -v'
                    sh 'npm -v'
                }
            }
        }
    }
}
