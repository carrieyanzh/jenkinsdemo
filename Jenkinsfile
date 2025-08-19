node {
    // Get NodeJS tool configured in Jenkins
    def nodeHome = tool name: 'NodeJS 20', type: 'NodeJS'
    env.PATH = "${nodeHome}/bin:${env.PATH}"

    stage('Build') {
        // Check Node.js and npm versions
        sh 'node -v'
        sh 'npm -v'

        // Install npm dependencies
        sh 'npm install'
    }
}
