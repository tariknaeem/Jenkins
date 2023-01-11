/* groovylint-disable CompileStatic */
pipeline {
    agent any
    stages {
        stage("Env check") {
            environment {
                SOME_USERNAME_PASSWORD = credentials('some-username-password')
                SOME_SECRET = credentials('some-secret')
            }
            steps {
                echo "SOME_USERNAME_PASSWORD ${SOME_USERNAME_PASSWORD}"
                echo "SOME_USERNAME_PASSWORD ${SOME_USERNAME_PASSWORD_USR}"
                echo "SOME_USERNAME_PASSWORD ${SOME_USERNAME_PSW}"
                echo "SOME_SECRET ${SOME_SECRET}"
            }
        }
    }
}
