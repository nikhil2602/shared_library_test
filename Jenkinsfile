@Library('jenkins-library@master') _
pipeline {
    agent any
    stages {
        stage('Git Checkout') {
            steps {
            gitCheckout(
                branch: "master",
                url: "https://github.com/nikhil2602/shared_library.git"
            )
            }
    }
    }
}
