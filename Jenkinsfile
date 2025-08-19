node {
     def mvnHome = tool name: 'Maven3', type: 'maven'
    env.PATH = "${mvnHome}/bin:${env.PATH}"

    stage('Build 1') {
        // Use 'sh' to run shell commands
        sh "mvn -version"
    }
    
    stage('Build') {
        def mvnHome = tool 'Maven3' // Must match name in Jenkins tool config
        sh "${mvnHome}/bin/mvn clean install"
        echo 'Starting Build Stage carrie build11---1'
        echo 'Build Stage completed successfully carrie build21'
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
