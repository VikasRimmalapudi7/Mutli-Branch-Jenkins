pipeline {
    agent any
    environment{
    branch="$GIT_BRANCH"
    }

    stages {
        stage('test') {
            steps {
                script {
                    echo "${env.branch}"
                }
            }
        }
    }
}
