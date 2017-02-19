pipeline {
  agent any
  tools {
    maven 'Maven 3.3.3'
    jdk 'JDK1.8'
  }
  stages {
    stage ('Initialization') {
      steps {
        echo 'Do you know this is the first words?'
        echo 'I am sceond here!'
        echo 'PATH = ${PATH}'
        bat '''
echo "path2 = ${PATH}"
echo "path3 = ${Path}"
        '''
      }
    }
  }
}
