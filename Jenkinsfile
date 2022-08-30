pipeline{
    agent any44
    stages{
        stage("one"){
            steps {
                echo "stage one Done."
            }
        }
        stage("whoami"){
            steps {
                sh "whoami"
            }
        }
        stage("hostname"){
            steps {
                sh "whoami"
            }
        }
        stage("ip"){
            steps {
                sh "ip a"
            }
        }
    }
}
