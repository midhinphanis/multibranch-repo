pipeline {
    agent any

    environment {
        NAME = "midhin"
        GAME = "cricket"
    }

    stages {
        stage('sport') {
            steps {
                echo "The player is ${env.NAME}"
                echo "He  plays ${env.GAME}"
            }
        }
    }
}
