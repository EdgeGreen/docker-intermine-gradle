node{
    
    stage ('Clone Repository'){
        git url: 'https://github.com/EdgeGreen/docker-intermine-gradle.git'
    }
	
	stage('Build image') {
        app = docker.build("edgegreen/builder-inter", "-f intermine_builder/intermine_builder.Dockerfile .")
    }   
}
