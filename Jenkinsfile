pipeline {
    agent any
    environment {
        GITNAME = 'pcmin929'
        GITMAIL = 'pcmin929@gmail.com'
        GITWEBADD = 'https://github.com/pcmin929/fast-code.git'
        GITSSHADD = 'git@github.com:pcmin929/fast-code.git'
        GITCREDENTIAL = 'git_cre'
        DOCKERHUB = 'oolralra/fast'
        DOCKERHUBCREDENTIAL = 'docker_cre'
    }
    stages {
        stage('start') {
            steps {
                sh "echo hello jenkins!!!"
            }
            post {
                failure {
                    sh "echo failed"
                }
                success {
                    sh "echo success"
                }
            }
        }
    }
}