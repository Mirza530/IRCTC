pipeline {
    agent any

    stages {
        stage('Implementation Stage') {
            steps {
                sh '''
                    ls -ltr
                    date
                    cal 2026
                '''

                sh '''
                    cat holidays.txt
                '''
            }
        }
    }
}
