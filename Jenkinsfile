pipeline {
    agent any
    stages {
        stage("build") {
            steps {
                echo "Building the app"
                script {
                    def test = 2+2 > 3 ? "Cool stuff": "Not Cool stuff"
                    echo test
                }
            }
        }

        stage("test") {
            steps {
                echo "Testing the app"
            }
        }

        stage("deploy") {
            steps {
                echo "Deploy the app"
            }
        }
    }
}
