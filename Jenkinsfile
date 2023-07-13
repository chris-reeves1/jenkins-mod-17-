pipeline {
    agent any
    stages {
        stage('Pipeline stage Build'){
            steps{
                sh "touch build.sh"
                sh 'echo "echo \'stage- Build\' > build.sh'
                sh "chmod +x build.sh"
                sh "./build.sh"
            }
        }        
    }
}
