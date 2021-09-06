pipeline{
agent any

stages{
stage('checkout'){
steps{
git 'https://github.com/krishna369865/githud-demo.git'
}
}
stage('build'){
steps{
sh 'mvn clean compile'
}
}
stage('test'){
steps{
sh 'mvn test'
junit 'reports/**/*.xml'
}
}
stage('deploy'){
steps{
sh 'deploying'
}
}
}
}


