pipeline {
    tools{
        jdk 'JAVA_HOME'
        maven 'M2_HOME'
    }
    agent any

    stages {
        stage('git clone') {
            steps {
                echo 'clone successfully completed'
            }
        }
        stage('compile') {
            steps {
                echo 'compile successfully completed'
            }
        }
        stage('test') {
            steps {
                echo 'test successfully completed'
            }
        }
        stage('package') {
            steps {
                echo 'package successfully completed'
            }
        }
    }
}
