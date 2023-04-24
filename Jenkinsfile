pipeline{
    agent 'any'
    tools{
        git 'git'
        maven 'maven' 
    }
    stages{
        stage('pull') {
            steps{
                sh 'git pull https://github.com/saigopsgit/project.git'
            }
        }

        stage('build'){
            steps{
                sh 'mvn package'
            }
        }



    }

    
}

