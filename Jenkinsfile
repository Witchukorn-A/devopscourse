pipeline {
    agent any

    stages {
        stage('Copy Git Repo') {
           steps {
              git 'https://github.com/Witchukorn-A/devopscourse.git'
              }
        }
        stage('Show Text') {
            steps {
                   sh 'cat README.md'
            }
        }
    }
}
