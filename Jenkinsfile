pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'master', url: 'https://github.com/NouraHossa/task2--repository--20216126.git'
            }
        }
        stage('Run Script') {
            steps {
                sh 'bash ./ls.sh'
            }
        }
    }
}
