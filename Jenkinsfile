properties(
  [
    pipelineTriggers(
      [
        [$class: 'GitHubPushTrigger']
      ]
    )
  ]
)

pipeline {

  /*
   * Run everything on an existing agent configured with a label 'docker'.
   * This agent will need docker, git and a jdk installed at a minimum.
   */
  agent any

  stages {

    stage('Test') {

      steps {
        sh "echo hello world from aws jenkins!"
        sh "echo other test"
        sh "echo other test"
      }

    }

  }

}
