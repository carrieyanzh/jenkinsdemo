pipeline {
  
    def nodeHome = tool name: 'NodeJS 20', type: 'NodeJS'
    env.PATH = "${nodeHome}/bin:${env.PATH}"
    
    stage('Build') {
        sh 'node -v'   // check Node.js version
    }   
}
