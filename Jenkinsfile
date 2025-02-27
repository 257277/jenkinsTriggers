pipeline{
    agent any
    stages{
        stage("A"){
            steps{
                echo "========executing A========"
            }
        }
    }
    stages("B")
    {
        steps{
            echo "first commit after aetting github webhook"
        }
    }
}