pipeline{
    agent{
        label{
            label "built-in"
            customWorkspace "/mnt/project123"
            
        }
    }
    stages{
        stage("one"){
            steps{
                sh "rm -rf *"
                sh "git clone https://github.com/RushikeshBorkar/practice123.git"
            }
        }
    }
    
}
