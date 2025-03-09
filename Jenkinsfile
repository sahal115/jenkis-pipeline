pipeline{
    agent any
    stages{
        stage('clone'){
            steps{
                sh 'clone'
            }

        }
stage('test'){
    steps{
        sh 'echo "test"'
    }
}
stage('createFile'){
    steps{
        sh 'touch text-$BUILD_ID'
    }
}            
        }
    
}