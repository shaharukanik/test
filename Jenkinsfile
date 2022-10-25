pipeline {
  agent { label "SlaveNode" }
  stages {
    stage("Multiple") {
	  steps {
	    sh "rmdir /tmp/testdir"
	    sh "df -h"
	    sh "free -h"
	  }
    }
  }
}
