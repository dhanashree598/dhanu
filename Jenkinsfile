pipeline {
    agent {
        label {
            label "built-in"
            customWorkspace "/mnt/velocity"
        }
    }    

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh "mkdir priya" 
            }
        }
    }
}
