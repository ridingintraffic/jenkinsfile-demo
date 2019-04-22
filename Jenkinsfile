pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
            
                
            }
        }
    }
    node {
    checkout scm
    def rootDir = pwd()
    println("Current Directory: " + rootDir)

    // point to exact source file
    def example = load "${rootDir}/file.Groovy"

    example.exampleMethod()
    example.otherExampleMethod() 
    }
}