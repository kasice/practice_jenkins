
node {
    stage('clone') {
git 'https://github.com/kasice/practice_jenkins.git'
}
stage('build') {
    sh lable: '', script: 'javac Main.java'
}
stage('Run') {
    sh label: '', script: 'java Main'
}
}
