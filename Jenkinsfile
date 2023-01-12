/* groovylint-disable CompileStatic */
pipeline {
    agent any
    stages {
        stage("checking ") {
            when {
                not {
                    branch 'main'
                }
             }
            steps {
                echo "run code"
            }
        }
    }
}
