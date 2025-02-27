pipeline {
    agent any

    stages {
        stage('Start') {
            steps {
                git branch: 'main', credentialsId: 'for_git_pipe', url: 'https://github.com/KiloByte328/for_course_abc/'
            }
        }
    }
}
