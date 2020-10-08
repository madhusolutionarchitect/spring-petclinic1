pipeline{
    agent{label 'master'}
    // agent{label 'slave1'}    
    tools{
        maven 'M3'
    }
    stages{
        stage('Checkout'){
            steps{
                git 'https://github.com/madhusolutionarchitect/spring-petclinic1'
            }
        }
        stage('Build'){
            steps{
                 sh 'mvn clean compile'
            }
        }
        }
}

