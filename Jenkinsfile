pipeline {
    agent any
    tools {
         gradle 'Gradle'   
    }

    stages {
        stage('Build') {
            steps {
                echo('Building Backend with Gradle.....')
                sh './gradle -v'
            }
        }
        stage('Test') {
            steps {
                echo('Testing.....')
            }
        }
        stage('Deploy') {
            steps {
                echo('Deploying.....')
            }
        }
    }
}
