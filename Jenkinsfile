pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                withMaven(maven : 'maven_3.6.0') {
                    sh 'mvn clean compile'
                }
            }
        }

    }
}
