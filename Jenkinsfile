pipeline {
  agent any
  triggers {
    pollSCM('* * * * *')
  }
  stages {
    stage("Compile") {
      steps {
        echo "./gradlew compileJava"
      }
    }
    stage("Unit test") {
      steps {
        echo "./gradlew test"
      }
    }
  }
}
