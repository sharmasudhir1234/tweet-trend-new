pipeline {
    agent {
        node{
            label "maven"
        }
    }

    stages {
        stage('clone-code') {
            steps {
                git branch: 'main', url: "https://github.com/sharmasudhir1234/tweet-trend-new.git"
            }
        }
    }
}
