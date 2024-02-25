properties([[$class: 'JobLocalConfiguration', changeReasonComment: ''], pipelineTriggers([pollSCM('H/30 * * * *')])])
node {
    stage("Checkout") {
        git branch: 'main', url: 'https://github.com/DrDrumm911/MySoftware.git'
    }
    stage("Build"){
        sh 'echo "Building..."'
    }
}
