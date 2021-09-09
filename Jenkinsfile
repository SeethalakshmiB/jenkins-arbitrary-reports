stage('Test') {
        node('linux') {
            checkout scm
            try {
                // unstash 'app'
                sh 'ls -lh'
            }
            finally {
                junit 'test.xml'
            }
        }
    }