pipeline{
    agent any 
    environment{
        NAME = "Midhin"
        MOVIE = "Spiderman"
    }
    stages{

        stage("watching"){
        when{
            allOf{
                expression { env.NAME == "Midhin"}
                expression { env.MOVIE == "Spiderman"}
            }
            anyOf{
                expression { env.NAME == "Midhin"}
            }
            steps{
                echo "${env.NAME} is watching ${env.MOVIE} "
            }
        }
        }
    
    }
}
