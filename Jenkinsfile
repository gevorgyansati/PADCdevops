node {
    dir('Student') {
        git branch: 'main', url: 'https://github.com/lessons2021/SatenGevorgyan.git'
    }
}
pipeline {
    agent any
    stages {
        stage("ugdanf") {
            steps {
                sh  "pytest Test.py"  
            }
        }
    }
}
