pipeline{
    agent any
    environment{
        NAME = "midhin"
        SPORT = "Football"
    }

    stages{
        stage('play')
        {
            when{
                anyOf{
                    expression { env.NAME == "midhin" }
                    expression { env.SPORT == "Cricket" } 
                }
            }
            steps{
            echo "${env.NAME} is playing ${env.SPORT}"
            }
        }
    }
}
