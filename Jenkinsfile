properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("clone") {
        git branch: 'master', url: 'https://github.com/Ikodzildo/MySoftware.git'
    }
    stage("show files"){
        sh "ls -l"
    }
}
