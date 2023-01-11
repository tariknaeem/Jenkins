pipeline {
    agent any
    environment {
        test = "uat"
    }
    stages {
        stage("test") {
            when {
                branch "main"
            }
        steps {
            echo "run code"
        }
        }
    }
}