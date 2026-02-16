pipeline{
    agent any
   
    stages{
        stage("Restore NuGet Packages"){
            steps{
                bat 'dotnet restore'
            }
            steps{
                bat 'dotnet build'
            }
            steps{
                bat 'dotnet test'
            }
        }
    }
}
