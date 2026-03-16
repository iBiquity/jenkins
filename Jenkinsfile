pipeline {
    agent any
    stages{
        stage("setup lambda"){
            agent {
                label "${platform}"
            }
            steps {
                echo "Setup lambda"
            }
        }
    }
}
