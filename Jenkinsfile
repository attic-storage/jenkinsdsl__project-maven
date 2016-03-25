node {
    docker.image('maven:3.3.3-jdk-8').inside {
        stage 'Checkout'
        checkout scm

        stage 'Build'
        maven 'clean install'

        stage 'Archive'
        archive 'target/*.jar'
    }
}