pipeline {
    agent any

    stages {
        stage ('first') {
            when { changeset "muthu.sh"}
            steps{
                sh ' ./muthu.sh'
            }
        }

        stage ('second') {
            when { changeset "inc.sh"}
            steps{
                sh ' ./inc.sh'
            }
        }
    }
}