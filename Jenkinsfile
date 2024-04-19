node {
    stage('Checkout code') {
        checkout scm
    }
    stage('Compile') {
        withGradle {
            sh './gradlew build --scan'
        }
    }
}
