node {
    stage('checkout') {
        checkout scm    
    }

    stage('Testing') {
        dir('fastlane') {
            sh 'fastlane test'
        }
    }

    stage('Run unit test') {

    }

    stage('Build') {

    }

    stage('Deploy') {
        
    }
}