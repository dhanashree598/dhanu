pipeline {
    agent {
        label {
            label "built-in"
            customWorkspace "/mnt/clone"
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
