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
                allOf{
                    expression { env.NAME == "midhin" }
                    expression { env.SPORT == "Football" } 
                }
            }
            steps{
            echo "${env.NAME} is playing ${env.SPORT}"
            }
        }
    }
}
