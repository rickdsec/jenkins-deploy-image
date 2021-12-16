
node {
    def app
    stage('Clone repository') {
        /* Cloning the Repository to our Workspace */
	    echo "Clone repo"
        checkout scm
    }

    stage('Build image') {
        echo "Building image"
        app = docker.build("rickd/nodeapp")
    }
        
}
