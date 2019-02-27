pipeline {
	agent any
    stages {
        stage ('checkout') {
            steps {
		checkout scm
            }
        }
        stage ('Build') {
            steps {
	             	sh 'rm -rf /etc/puppetlabs/code/environments/production/modules/mymodule/files/*'
                sh 'cd /home/zippyops/workspace
                sh 'mv -f angularjs/**/**  /etc/puppetlabs/code/environments/production/modules/mymodule/files/' 
	    }
          } 
    }
}
