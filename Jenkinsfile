pipeline {
agent any&lt;/code&gt;
 
tools{
maven 'maven 3'
jdk 'java 8'
}
 
stages {
stage ("initialize") {
steps {
sh '''
echo "PATH = ${PATH}"
echo "M2_HOME = ${M2_HOME}"
'''
}
}
stage ('Build project') {
steps {
dir("java_web_code"){
sh 'mvn clean verify
 
}
}
}
