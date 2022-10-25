pipeline {
  agent { label "SlaveNode" }
  stages {
    stage("Create Directory") {
	  steps {
	    sh "rmdir /tmp/testdir"
      }
	}
  }
}
