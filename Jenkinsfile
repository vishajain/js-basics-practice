pipeline {
    agent { docker { image 'node:16.13.1-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
                echo 'building the application'
            }
        }
        stage('test'){
            steps {
                echo  'testing the application'
        }
      }
       stage('deploy'){
            steps {
                echo  'deploying the application'
        }
      }
    }
}
