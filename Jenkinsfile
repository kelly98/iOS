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
        dir('fastlane') {
            sh 'fastlane buildApp'
        }
    }

    stage('Deploy') {
        
    }
}