pipeline {
    agent {
        label 'docker'
    }

    parameters {
        choice choices: ['no', 'yes'], description: 'Are you sure, you want to deploy?', name: 'action'       
    }

    stages {
        stage('deploy to minikube'){
            steps { 
                echo '''
                    hello branch build dev3 v1
                '''
            }
        }
    }
}
