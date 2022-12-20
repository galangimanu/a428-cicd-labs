node {
    docker.image('node:lts-bullseye-slim')

        stage('build') {
            sh './jenkins/scripts/npm_install.sh'
    }

        stage('test') {
            sh './jenkins/scripts/test.sh'
        }

}
