pipeline{
    agent none
    stages {
        stage("first"){
            steps {
                timestamps {
                      logstash{ 
                       echo "hello world 3"
                      }
                  
                }
            }
        }
        stage("second"){
            steps{
                timestamps {
                    logstash {
                        echo "hello world 4"
                    }
                }
            }
        }
    }
}
