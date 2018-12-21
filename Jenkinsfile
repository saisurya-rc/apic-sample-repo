pipeline {

    agent any

    stages {
        stage("CHECKOUT") {
            steps {
                checkout scm
            }
        }
        post {
            always {

                echo "Git checkout completed."
            }
        }
    }

}