node {
        stage('Test') {
                checkout scm
                // try {
                    // unstash 'app'
                    sh 'ls -lh'
                // }
                // finally {
                    junit 'xml/test.xml'
                    publishHTML (target : [allowMissing: false, alwaysLinkToLastBuild: true, keepAll: true, reportDir: 'html', reportFiles: 'index.html', reportName: 'My Reports', reportTitles: 'The Report'])
                    archiveArtifacts 'sample.txt'
                // }
        }
    }