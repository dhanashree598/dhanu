pipeline {
    agent {
        label {
            label "built-in"
            customWorkspace "/mnt/clone-1"
        }
    }    

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh "mkdir priya-1" 
            }
        }
    }
}
