pipeline{
    agent any
        stages{
            stage('stage_1'){
                steps{
                    echo 'This is stage ONE'

                }

            }
            stage('parallel'){
                parallel{
                    steps('on Branch A'){
                        echo "ON BRANCH A"
                    }
                    steps('on branch B'){
                        echo "ON BRANCH B"
                    }
                }
            }

        }
}
