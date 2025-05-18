pipeline {

    agent any

    stages {

        stage("hello") {
            steps {
                echo "hello world"
            }
        }
    
        stage("test1") {
            steps {
                echo "test webhook"
            }
        }

        stage("deploy") {
            steps {
                echo "end of pipelines"
            }
        }

        stage("Execute shell") {
            steps {
                sh('chmod +x ./scripts/test.sh')
                sh('./scripts/test.sh')
            }
        }

        stage("End") {
            steps {
                echo "end of pipeline"
            }
        }

        


    }
}
