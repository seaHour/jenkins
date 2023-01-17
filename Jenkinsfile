pipeline {
  agent any
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
