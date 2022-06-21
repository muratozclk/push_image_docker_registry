pipeline {

    agent any
    stages {
            stage('Push Docker Image Registry') {
                steps {
                    sh "docker tag node-web-app server-3.ozcelik.tk:5000/node-web-app"
                    sh "docker push server-3.ozcelik.tk:5000/node-web-app"
                }
            }

        }
    }
