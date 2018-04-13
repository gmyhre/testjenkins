Jenkinsfile (Declarative Pipeline)
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
            	cd /Users/gmyhre/ && sh grahamTest.sh
                sh 'echo "Hello World" > myFileeee'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '' > myFileeee'
            }
        }
    }
}