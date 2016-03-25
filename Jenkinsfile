node {
    stage 'Checkout'
    checkout scm
    
    input 'Tu veux compiler?'
    input 'Tu es sûr?'

    stage 'Build'
    maven 'clean install'

    stage 'Archive'
    archive 'target/*.jar'
}
