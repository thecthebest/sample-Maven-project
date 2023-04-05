pipeline {
    agent any
    stages {
        stages {
  stage('maven install') {
    steps {
      // One or more steps need to be included within the steps block.
      withMaven(globalMavenSettingsConfig: '--- Use system default settings or file path ---', jdk: '--- Use system default JDK ---', maven: 'maven3', mavenSettingsConfig: '--- Use system default settings or file path ---') {
    // some block
        sh 'mvn clean install'
}
    }
  }

}

    }
}


