/* groovylint-disable-next-line CompileStatic */
/* groovylint-disable-next-line NglParseError */
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
                    stage('Branch A') {
                        steps {
                            echo "ON branch A"
                        }
                    }
                    stage('Branch B') {
                        steps {
                            echo "On branch B"
                        }
                    }
                   
            }

        }
}
