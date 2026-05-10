pipeline {
    agent any

    environment {
        PATH = "/opt/maven/bin:${env.PATH}"
    }

    stages {

        stage("Git Clone") {
            steps {
                git url: 'https://github.com/Mirza530/IRCTC.git', branch: 'main'
            }
        }

        stage("Build") {
            steps {
                sh 'mvn clean install'
            }
        }

    }
}
