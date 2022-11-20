pipeline {
    agent any
    stages {
        stage('print') {
            steps {
                script {
                    def data = readFile(file: 'README.md')
                    println(data)
                }
            }
        }
    }
}
