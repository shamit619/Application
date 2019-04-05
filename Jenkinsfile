pipeline {
    agent { label 'master' }
    stages {
        stage('ImageCreation') {
            steps {
                echo "Downloading Sonatype/nexus3 image from docker hub....."
            }
            stage('Kube8Deployment') {
                steps {
                echo "Deploying nexus application using kubernetes......."
                }
            }
        }
    }
}
