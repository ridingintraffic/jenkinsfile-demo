def modules = [:]
pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                script{
                    modules.first = load "file.groovy"
                    modules.second.init(modules.first)
                    modules.first.test1()
                }
            }
        }
    }
}