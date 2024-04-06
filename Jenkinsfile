pipeline {
    agent {label "kubeagent"}


    stages {
        stage('Build Docker Image') {
            steps {
                script {
                    docker.build("hello-world-dotnet-docker")
                }
            }
        }

    }
}
