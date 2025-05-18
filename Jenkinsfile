pipeline {

    agent any

    stages {

        stage("hello") {
            steps {
                echo "hello world"
            }
        }
    
        stage("test") {
            steps {
                echo "test webhook"
            }
        }

        stage("deploy") {
            steps {
                echo "end of pipelines"
            }
        }

        stage("End") {
            steps {
                echo "end of pipeline"
            }
        }

    }
}