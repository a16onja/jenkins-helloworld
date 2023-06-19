node {
    stage('clone') {
        git credentialsId: 'onja', url: 'https://github.com/a16onja/jenkins-helloworld.git'
    }
    stage('build') {
        sh 'javac Main.java'
    }
    stage('run') {
        sh 'java Main'
    }
}
