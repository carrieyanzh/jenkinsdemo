node {
    def nodeHome = tool name: 'NodeJS 20', type: 'NodeJS'
    env.PATH = "${nodeHome}/bin:${env.PATH}"
    sh 'node -v'
    sh 'npm -v'
}
