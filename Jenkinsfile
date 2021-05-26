pipeline {
  agent any
  stages {
       stage ('DAST') {
         steps {
          sh 'docker run -t owasp/zap2docker-stable zap-baseline.py -t http://192.168.5.30:8080 || true'
        }
      }
       }
  }

