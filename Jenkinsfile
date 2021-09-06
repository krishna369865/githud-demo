pipeline{
tools{
maven M3
}
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
}
}
stage('deploy'){
steps{
sh 'deploying'
}
}
}
}


