//SCRIPTED




//DECLARATIVE

pipeline {
        agent any
        stages {
            stage('Build'){
                steps{
                      echo "Build"
                }
            }
                        stage('Test'){
                            steps{
                            	echo "Test"
                            }
                        }
                                    stage('Integration Test'){
                                        steps{
                                            echo "Integration Test"
                                        }
                                    }
      } post{
            always{
                echo 'Im awsome. I run always'
            }
            succes{
                echo 'I run when you are succesful'
            }
            failure{
                 echo 'I run when you fail'
            }
      }

}
