#!/usr/bin/env groovy
// Jenkinsfile (Declarative Pipeline)
pipeline {
  agent {label 'ubuntu_slave'}
  stages {
    stage('Build') {
        steps {
        sh 'echo "This is my first step"'
        }
    }
    stage('Test') {
        steps{
        sh 'echo "This is my Test step"'
        }
    }
    stage('Deploy') {
        steps {
        sh 'echo "This is my Deploy step"'
        }
    }
  }
}
