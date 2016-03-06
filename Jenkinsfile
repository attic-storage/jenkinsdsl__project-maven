node {
    stage 'Checkout'
    checkout scm

    stage 'Build'
    maven 'clean install'

    stage 'Archive'
    archive 'target/*.jar'
}