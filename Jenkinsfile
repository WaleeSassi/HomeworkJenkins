pipeline{
    agent any
    stages{
       stage('hello'){
            steps{
               echo "hello world"
                
            }
        }
        stage('testing maven'){
            steps{
               sh """mvn --version"""
                
            }
        }
        stage('git checkout'){
              steps{
                 git branch : "main",
                  url:"https://github.com/WaleeSassi/HomeworkJenkins"
                  
              }
          }
    }
}
