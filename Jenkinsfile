@Library('piper-lib-os') _

node(){
    stage('init'){
        deleteDir()
        checkout scm
        echo 'init-test'
    }
    stage('deployIntegrationArtifact Command'){
        integrationArtifactDeploy script: this
    }
}