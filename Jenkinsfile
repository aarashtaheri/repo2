pipeline {
    agent any
    parameters {
      choice(name: 'door_choice:', choices:'one\ntow\ntree\nfour', description:'What door do you choose?'
    }
    stages {
        stage('Example') {
            steps {
                echo "Trying ${params.door_choice}"
            }
        }
    }
}
