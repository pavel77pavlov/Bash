pipeline {
    agent any 
    parameters {
                    string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
                }
    stages {
        stage {
            
            parallel{
                stage('Test1') { 
                    steps {
                        echo "First Pipeline"
                    }
                }
                stage('Test2') {
                    steps {
                        echo " New stage add for ${PERSON} and this is all.."
                    }
                }
            }
        }    
    }
}
