pipeline{
    agent any

    parameters{
        string (
            name: 'User',
            defaultValue: 'Midhin', 
            description: 'Who is the user'
        )
        booleanParam(
            name: 'TOGGLE',
            defaultValue: true,
            description: 'TOGGLE this value'
        )
         choice(
            name: 'CHOICE', 
            choices: ['One', 'Two', 'Three'], 
            description: 'Pick something'
        )
    }
    stages{
        stage('parameters'){
            steps{
                echo "The user is ${params.User}"
                echo "The user is toggled with ${params.TOGGLE}"
                echo "The user choice is ${params.CHOICE}"
            }
        }
    }
}
