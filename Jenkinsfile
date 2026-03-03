pipeline {
  agent any

  stages {

    stage('Clone') {
      steps {
        git url: 'https://github.com/Mayur-2403/jenkin-demo.git',
            branch: 'main'
      }
    }

    stage('Run Python Script') {
      steps {
        sh 'python3 --version'      // optional (check Python)
        sh 'python3 script.py'      // run python file
      }
    }

  }
}
