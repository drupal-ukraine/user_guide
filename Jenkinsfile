pipeline {
    agent {
        docker { image 'andriyun/drupal-user-guide-builder' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'cd scripts && ./mkoutput.sh'
            }
        }
    }
}
