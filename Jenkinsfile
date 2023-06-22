pipeline {
    agent any
    stages {
        stage('Clean') {
            steps {
               sh "C:\Users\rajin\Downloads\apache-maven-3.9.2\bin\mvn clean"
             }
         }
        stage('Build') {
            steps {
               sh "/Users/rajin/Downloads/apache-maven-3.9.2/bin/mvn compile"
             } 
         } 
        stage('Test') {
            steps {
               sh "/Users/rajin/Downloads/apache-maven-3.9.2/bin/mvn  test -DskipTests=true"
             }
         }
     }
}


