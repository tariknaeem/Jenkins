pipeline {
    agent any
    environment {
        SOME_NAME = "uat"
    }
    stages {
        stage("When Test with equals") {
            when {
                equals expected: "uat" actual: SOME_NAME
            }
        steps {
            echo "${SOME_NAME}"
        }
        }
    }
}