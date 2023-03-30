pipeline {
    agent linux

    stages {
        stage('Build') {
            steps {
                snDevopsChangePipeline applicationName: "hello", sandboxName: "sand", buildVersion: "1.0"
            }
        }
    }
}
