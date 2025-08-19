node {  
    agent { lable 'Built-In Node aaaa' }
    tools {
        maven 'Maven3'  // name configured in Jenkins tools
    }
    stage('Build') { 
        sh 'mvn clean install'
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
