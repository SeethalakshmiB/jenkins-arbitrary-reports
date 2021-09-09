node {
        stage('Test') {
            steps {
                checkout scm
                // try {
                    // unstash 'app'
                    sh 'ls -lh'
                // }
                // finally {
                    junit 'test.xml'
                // }
            }
        }
    }