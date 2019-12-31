pipeline{
    agent none
    stages {
        stage("hello3"){
            steps {
                timestamps {
                      logstash{ 
                       echo "hello world 3"
                      }
                  
                }
            }
        }
        stage("hello4"){
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
