pipeline {
  /*
   * TODO: Implement pipeline stages/steps
   *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
   */
  // See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
    agent any
    stages {
        stage("Build") {
            steps {
                echo "./gradlew assemble"
            }
        }
        stage("Test") {
            steps {
                sh "./gradlew test"
            }
        }
    }
}
