node {
        stage('Test') {
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