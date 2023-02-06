pipeline {
    agent any
    stages {
        stage('git clone'){
            steps {
                git branch: 'main', url: 'https://github.com/gaju569/dec-pipeline.git'
            }
        }    
        stage('test the code'){
            steps {
                echo "testing is completed"
                
            }
        }    
        stage('build the code'){
            steps {
                echo "code is built"
            }    
        }    
    }     
}
