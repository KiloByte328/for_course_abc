pipeline {
    agent any

    stages {
        stage('Start') {
            steps {
                checkout scmGit(branches: [[name: 'main']], extensions: [], userRemoteConfigs: [[credentialsId: 'for_git_pipe', url: 'https://github.com/KiloByte328/for_course_abc/']])
                git branch: 'main', credentialsId: 'for_git_pipe', url: 'https://github.com/KiloByte328/for_course_abc/'
            }
        }
    }
}
