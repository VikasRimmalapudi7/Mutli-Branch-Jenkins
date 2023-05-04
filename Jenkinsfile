pipeline {
    agent any
    environment{
                    Git_branch = "$GIT_BRANCH"
                    Git_previous_commit = "$GIT_PREVIOUS_COMMIT"
                    Git_successful_commit = "$GIT_PREVIOUS_SUCCESSFUL_COMMIT"
                    Git_url = "$GIT_URL"
                    Git_author = "$GIT_AUTHOR_NAME"
                    Git_committer_email = "$GIT_COMMITTER_EMAIL"
                     
 
    }

    stages {
        stage('test') {
            steps {
                script {
                     echo "${env.Git_branch}"
                     echo "${env.Git_previous_commit}"
                     echo "${env.Git_successful_commit}"
                     echo "${env.Git_url}"
                     echo "${env.Git_author}"
                     echo "${env.Git_committer_email}"
                    
                }
            }
        }
    }
}
