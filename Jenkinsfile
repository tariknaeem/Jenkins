/* groovylint-disable GStringExpressionWithinString, UnnecessaryGString */
/* groovylint-disable-next-line CompileStatic */
pipeline {
    agent any
    environment {
        name1 = "Jeff"
        name2 = "Mark"
    }
    stages {
        stage("Checkout") {
            environment {
                name3 = "Michelle"
            }
            steps {
                echo "name1 is ${name1}"
                echo "name2 is ${name2}"
                echo "name3 is ${name3}"
            }
        }
    }
}
