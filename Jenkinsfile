pipeline{
    agent any
   
    stages{
        stage("Restore NuGet Packages"){
            steps{
                bat 'dotnet restore'
            }
        }
         stage("Build project"){
            steps{
                bat 'dotnet build'
            }
        }
         stage("Test Project"){
            steps{
                bat 'dotnet test'
            }
        }
    }
}
