pipeline {
  agent { label "SlaveNode" }
  stages {
    stage("Multiple") {
	  steps {
	    sh "mkdir /tmp/testdir"
	    sh "cd /tmp/testdir"
	    sh "touch file-99"
	  }
    }
  }
}
