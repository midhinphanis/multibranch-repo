pipeline {
    agent any

    environment {
        NAME = "midhin"
        GAME = "cricket"
    }

    stages {
        stage('sport') {

            environment{
                NAME = "kartheek"
            }
            when{
                expression{
                    env.NAME == "midhin"
                }
                
            }
            steps {
                echo "The player is ${env.NAME}"
                echo "He  plays ${env.GAME}"
            }
        }
    }
}
