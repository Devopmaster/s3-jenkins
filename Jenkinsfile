pipeline {
    agent {
        label {
            label "built-in"
            customWorkspace "/yyy"
            }
    }

    stages {
        stage ("make-s3-bucket") {
            steps {
                    sh "aws s3 mb s3://mark88"
                    sh "aws s3 cp index.html s3://mark88"
            }
            

        }


    }




}
