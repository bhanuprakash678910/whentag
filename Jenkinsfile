pipeline {
    agent any
    stages {
        stage("Build Master") {
            when {
              buildingTag()
            }
            steps {
                echo "Hello World Building Tag"
            }
        }
    }
  }
