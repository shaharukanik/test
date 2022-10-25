pipeline {
  agent { label "SlaveNode" }
  stages {
    stage("Browser Test") {
	  parallel {
	    stage("Brave Test") {
		  steps {
		    echo "Test Brave"
		  }
		}
		stage("Chrome Test") {
		  steps {
		    echo "Test Chrome"
		  }
		}
		stage("Firefox Test") {
		  steps {
		    echo "Test Firefox"
		  }
		}
		stage("Safari Test") {
		  steps {
		    echo "Test Safari"
		  }
		}
		stage("Opera Test") {
		  steps {
		    echo "Test Opera"
		  }
		}
	  }
	}
	stage("Fly") {
	  steps {
	    echo "Fly"
	  }
	}
	stage("To") {
	  steps {
	    echo "To"
	  }
	}
	stage("The") {
	  steps {
	    echo "The"
	  }
	}
	stage("Moon") {
	  steps {
	    echo "Moon"
	  }
	}
  }
}
