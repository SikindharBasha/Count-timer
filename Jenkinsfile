pipeline {
    agent any
tools{
    maven 'maven'
}
    stages {
        stage('Clone code from git') {
            steps {
                git 'https://github.com/SikindharBasha/Count-timer.git'
            }
        }
          stage('Build the code') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}
