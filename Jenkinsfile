pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/mamatajadhav2004-jpg/Mamata_2004.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }
    }
}
