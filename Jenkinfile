node {
    stage('git clone') {
        git 'https://github.com/vdubreu/helloVincent-java.git'
    }
    stage('build and run') {
        sh 'javac Main.java'
        sh 'java Main'
        sh 'java -version'
    }
}