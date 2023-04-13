pipeline {

    agent any{

        docker { image 'buildpacksio/pack:latest' }

    }

    stages {

        stage('Test') {

            steps {

                sh 'pack build ...'

            }

        }

    }

}


