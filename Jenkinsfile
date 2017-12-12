pipeline {
    agent {
        docker { image 'andriyun/drupal-user-guide-builder' }
    }
    stages {
        stage('Test') {
            steps {
                echo 'uk' > scripts/languages.txt
                scripts/mkoutput.sh
            }
        }
    }
}
