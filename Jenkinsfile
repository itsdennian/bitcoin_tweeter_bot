pipeline { 
    agent any 
    stages {
      stage('Unit tests') { 
                  steps { 
                sh '''
                pip install virtualenv
                echo $PATH
                ls
                pwd
                virtualenv env -p python3.5
                . env/bin/activate
                pip install -r requirements.txt
                '''



}
      }
        }
    }
