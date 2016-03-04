node {
    stage 'Checkout'
    checkout scm
    stage 'Build'
    sh "${tool 'Maven 3.x'}/bin/mvn"
    stage 'Archive'
    archive 'target/*.jar'
}