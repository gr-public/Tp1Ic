#!/usr/bin/env groovy

pipeline {
    agent any

    stages {
        stage("package") {
            steps {
                checkout scm
                sh 'mvn package'
            }
        }
    }
}
