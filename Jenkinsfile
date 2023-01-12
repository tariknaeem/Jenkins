/* groovylint-disable CompileStatic */
pipeline {
    agent any
    stages {
        stage("checking ") {
            when {
                not {
                    branch 'origin/main'
                }
             }
            steps {
                 sh "printenv"
            }
        }
    }
}
