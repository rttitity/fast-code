pipeline {
    agent any
    environment {
        GITNAME = 'rttitity'
        GITMAIL = 'jinwoo25803@gmail.com'
        GITWEBADD = 'https://github.com/rttitity/fast-code.git'
        GITSSHADD = 'git@github.com:rttitity/fast-code.git'
        GITCREDENTIAL = 'git_cre'
        DOCKERHUB = 'giga0zinucha/fast'
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