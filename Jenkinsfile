pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('clone-code') {
            steps {
                git branch: 'main', url:'https://github.com/SenaitDe/tweet-trend-new.git'
            }
        }
    }
}