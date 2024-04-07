pipeline {
    agent{ 
        node{
             label 'maven'// some block
        }
    }    


    stages {
        stage('Clone-code') {
            steps {
                git branch: 'main', url: 'https://github.com/ravdy/tweet-trend-new.git'
            }
        }
    }
}