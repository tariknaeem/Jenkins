
/* groovylint-disable-next-line CompileStatic */
pipeline {
    agent any
    environment {
        DEPLOY_TO = "production"
    }
    stages {
        stage("Test") {
            when {
                /* groovylint-disable-next-line DuplicateStringLiteral */
                environment name: "DEPLOY_TO", value: "production"
            }
            steps {
                echo "Deploying to ${DEPLOY_TO}"
            }
        }
    }
}
