pipeline {
    agent any

    stages {
        stage('STAGE1:BUILD') {
            steps {
        sh '''
	#!/bin/bash        
        echo "this is a script"
	cd /home/ec2-user/git-practice/c-project/
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
