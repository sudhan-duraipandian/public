pipeline {
agent any
stages {
        stage('git checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/sudhan-duraipandian/public.git'
            }
        }
        stage('execute the file') { 
            steps {
                 sh 'bash test.sh'
            }
        }
}
