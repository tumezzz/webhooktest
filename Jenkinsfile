properties([pipelineTriggers([[$class: 'GitHubPushTrigger'], pollSCM('H/15 * * * *')])])

pipeline {

  /*
   * Run everything on an existing agent configured with a label 'docker'.
   * This agent will need docker, git and a jdk installed at a minimum.
   */
  agent {
    node {
      //label 'docker'
    }
  }

  stages {

    stage('Test') {

      steps {
        sh "echo hello world!"
      }

    }

  }

}
