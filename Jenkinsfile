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
		sh 'rm -rf /etc/puppetlabs/code/environments/production/modules/mymodule/files/Angularjs/*'
                sh 'mv -f /home/zippyops/workspace/angular/* /etc/puppetlabs/code/environments/production/modules/mymodule/files/Angularjs/' 
	    }
          } 
    }
}


 
