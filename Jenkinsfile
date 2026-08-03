pipeline{
    agent any
    stages{
        stage('Tools')
         tools{
                maven "maven-3.6.3"
            }
        steps{

            sh 'mvn --version'
        }
    }
}
