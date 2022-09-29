node {
    dir('Student') {
        git branch: 'main', url: 'https://github.com/gevorgyansati/PADCdevops.git'
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
