pipeline {
    agent any 
    parameters {
                    string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
                }
    stages {
        stage('Test') { 
            steps {
                echo "First Pipeline"
            }
        }
        stage('Build') {
            steps {
                echo " New stage add for ${PERSON} and this is all.."
            }
        }
    }
}
