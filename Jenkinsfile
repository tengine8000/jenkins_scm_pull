pipeline{
    agent any
    parameters{
        string(name: 'Greeting', defaultValue: 'Hello', description: 'How should I greet the world?')
    }
    stages{
        stage('Build'){
            steps{
                sh 'echo' "Hello World!"
                sh ''' 
                    echo "Multiline shell steps work too"
                    ls -lah
                '''
            }
        }
    }
}
