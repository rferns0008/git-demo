pipeline {
	agent any
	stages {
	       stage ("code cloning") {
		    steps {
			git 'https://github.com/rferns0008/git-demo.git'
			echo "Cloning the code"
		    }
	       }

	       stage ("(cde build") {
		    steps {
			echo "Building the image"
		    }
	       }

	       stage (" deploy") {
		    steps {
			echo "Deploy the image"
		    }
	       }
	}
}
