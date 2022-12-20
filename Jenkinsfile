node {
    docker.image('node:lts-bullseye-slim').inside {
        stage('build') {
            sh 'npm install'
    }
    }

        stage('build') {
            sh 'npm install'
    }

        stage('test') {
            sh './jenkins/scripts/test.sh'
        }

}
