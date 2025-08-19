node ('test-server'){
    mvnHome = tool name: 'Maven3', type: 'maven'
    env.PATH = "${mvnHome}/bin:${env.PATH}"

    stage('Build') {
        // Use 'sh' to run shell commands
        sh "mvn -version"
    }
    
   
    stage('Test') {
        echo 'Starting Test Stage carrie test12'
        echo 'Test Stage completed successfully carrie test22'
    }
    stage('Deploy') {
        echo 'Starting Deploy Stage carrie deploy13'
        echo 'Deploy Stage completed successfully carrie deploy23'
    }
}
