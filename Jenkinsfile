Jenkinsfile (Declarative Pipeline)
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"' > myFileeee
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                ''' > myFileeee
            }
        }
    }
}