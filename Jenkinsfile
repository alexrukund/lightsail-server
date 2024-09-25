pipeline{
    agent any
    stages{
        stage("terraform init"){
            steps {
                sh "terraform init"
            }
        }
         stage("terraform validate"){
            steps {
                sh "terraform validate"
            }
        }
            tage("terraform fmt"){
            steps {
                sh "terraform fmt"
            }
        }
         
        tage("terraform validate"){
            steps {
                sh "terraform validate"
            }
        }
            
        tage("terraform plan"){
            steps {
                sh "terraform plan"
            }
        }
    }
}