#!groovy
node { // <1>
	echo "Hello World"
	stage('Build') {  // <2>
		/* stage1 comment */
		checkout scm
		echo "Build stage"
		build job: 'testProject', quietPeriod: 5
	}
	stage('Test') {
		echo "Test stage"
	}
	stage('Deploy') {
		echo "Deploy stage"
	}
}
