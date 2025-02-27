pipeline{
    agent any
    stages{
        stage("A"){
            steps{
                echo "========executing A========"
            }
        }
        stage("B")
        {
            steps{
                echo "first commit after setting github webhook"
            }
        }
         stage("C")
        {
            steps{
                echo "first commit after setting Poll SCM"
            }
        }
    }
    
}