stage('Security Scan') {
    steps {
        sh 'trivy image --exit-code 1 --severity CRITICAL,HIGH nginx:stable'
    }
}
