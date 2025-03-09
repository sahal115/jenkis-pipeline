pipeline{
    agent any
    stages{
        stage('clone'){
            steps{
                sh 'echo "clone"'
            }

        }
stage('test'){
    steps{
        sh 'echo "test"'
    }
}
stage('CreateFile'){
    steps{
        sh 'touch text-$BUILD_ID'
    }
}            
        }
    
}