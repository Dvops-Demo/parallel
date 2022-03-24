/* groovylint-disable-next-line CompileStatic */
pipeline {
    agent any

        stages {
            stage('Non parallel') {
                steps {
                    echo 'This is stage ONE'

                }

            }
            stage('parallel') {
                parallel {
                    steps {
                        echo "ON BRANCH A"
                    }
                    steps {
                        echo "ON BRANCH B"
                    }
                }
            }

        }
}
