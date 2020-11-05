pipeline {
    agent any
    stages {
        stage('Clone Repositories') {
            steps {
                dir('opencv'){
                    git branch: 'master', credentialsId: '201cce05-517b-4112-ba59-f89ecfc9a5de', url: 'https://github.com/zynabsmaan/Spatial-Pyramid-matching---classification.git'
                    }
            }
        }
        stage("building") {
            steps {
            echo "building ......"
            
            }
        }
        
        stage("testing") {
            steps {
            echo "testing ......"
            
            }
        }
        
        stage("deploying") {
            steps {
            echo "deploying ......"
            
            }
        }
    }
    

}
