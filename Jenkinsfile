pipeline {
  agent any
  stages {
    stage('Print Hostname') {
      steps {
        sh 'hostname'
      }
    }
    stage('Ip address') {
      steps {
        sh 'hostname -i'
      }
    }
    stage('CPU details') {
      steps {
          sh 'lscpu'
      }
    }
    stage('Disk usage'){
      steps {
        sh 'df -kh'
      }
    }
    stage('Memory usage') {
      steps {
        sh 'free -h'
      }

    }
  }
}
