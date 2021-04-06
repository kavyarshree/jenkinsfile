pipeline {
    agent any

    stages {
        stage('STAGE1:BUILD') {
            steps {
        sh '''
	#!/bin/bash        
        echo "this is a script"
	git clone https://github.com/kavyarshree/c-project.git
	cd /home/ec2-user/workspace/c-project/
	make
	'''
            }
        }
stage('STAGE2') {
            steps {
                echo 'this is test stage'
    }
}

}
}
