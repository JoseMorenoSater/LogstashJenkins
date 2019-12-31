pipeline{
    agent none
    stages {
        stage("hello1"){
            steps {
                timestamps {
                      logstash{ 
                       echo "hello world 1"
                      }
                  
                }
            }
        }
        stage("hello2"){
            steps{
                timestamps {
                    logstash {
                        echo "hello world 2"
                    }
                }
            }
        }
    }
}
