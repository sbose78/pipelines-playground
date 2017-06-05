#!/usr/bin/groovy
@Library('https://github.com/jenkinsci/workflow-durable-task-step-plugin@master')
pipeline {
    agent { docker 'maven:3.3.3' }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
