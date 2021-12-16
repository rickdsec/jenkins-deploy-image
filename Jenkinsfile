node {  
    def app
    stage('Clone repo ') { 
        echo "Clone repo"
        checkout scm 
    }
    stage('building image') { 
        echo "Building image"
        app = docker.build("rickd/nodeapp") 
    }
    stage('Deploy') { 
        // 
    }
}
