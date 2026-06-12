pipeline {
agent any
stages {
stage('Clone Code') {
steps {
git branch: 'master', url: 'https://github.com/swethaj2005/jenkins-demo.git'
}
}
stage('Compile Code') {
steps {
bat 'javac hello.java'
}
}
stage('Run Code') {
steps {
bat 'java hello'
}
}
}
}
