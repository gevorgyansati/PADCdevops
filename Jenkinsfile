pipeline {
    agent any
    stages {
        stage("clone") {
            steps {
                sh "git clone https://github.com/gevorgyansati/PADCdevops.git"
            }
            
        stage("ugdanf") {
            steps {
                sh "cd PADCdevops"
                sh  "pytest Test.py"  
            }
        }
    }
}
