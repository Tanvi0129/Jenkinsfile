node{
   stage('git clone'){
    git credentialsId: 'pardu', url: 'https://github.com/Tanvi0129/Jenkinsfile.git'
    }
    stage('maven clean'){
	   sh 'mvn clean'
	}
	stage('maven Validate') {
	   sh 'mvn validate'
    }
	stage('maven Compile') {
	   sh 'mvn compile'
	}
	stage('maven Test') {
	   sh 'mvn test'  
	}
	stage('maven Deploy'){
	   sh 'mvn deploy'
	}
	stage('maven package'){
	   sh  'mvn package'
	}
	}