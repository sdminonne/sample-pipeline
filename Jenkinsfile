pipeline {
    agent { docker { image 'golang' } }
    stages {
        stage('build') {
            steps {
                sh 'go version'
		sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}