pipeline{
    agent any
    tools{
        maven '3.9.4'
    }
    stages{
        stage('Example'){
            steps{
                sh 'mvn --version'
                sh 'mvn -B -DskipTests clean package'

            }
        }
    }
}