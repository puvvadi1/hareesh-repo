pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('hi') {
            steps {
                echo 'Welcome to job1 inside stage'
	    }
        }
        stage('parallel stages') {
            parallel {
                stage('parallel1') {
                    steps {
                        echo 'Welcome to parallel1'
                    }
                }
                stage('parallel2') {
                    steps {
                        echo 'Welcome to parallel2'
                    }
                }
            }
        }
        stage('bye') {
            steps {
                echo 'done all the steps'
            }
        }
    }
}


