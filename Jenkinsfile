pipeline {
    agent any
    stages {	
        stage('run-parallel-branches') {
          steps {
            parallel(
              a: {
                echo "This is branch a"
                touch "C:\Users\kumar\Desktop\abc.txt"
              },
              b: {
                echo "This is branch b"
              }
            )
          }
        }
    }
}
