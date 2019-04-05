pipeline {
    agent { label 'master' }
    stages {
        stage('ImageCreation') {
            steps {
                echo "Downloading Sonatype/nexus3 image from docker hub....."
            }
            stage('Kube8Deployment') {
                echo "Deploying nexus application using kubernetes.......
            }
        }
    }
}
