pipeline {
    agent any
    stages{
        stage('compile'){
            steps{
                echo 'Compile Successfully'
            }
        }

    stage('Unit test'){
        steps{
            sh python test.py
        }
    }
    }
}