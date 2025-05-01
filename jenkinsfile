pipeline
{
	agent any
	stages
	{
		stage('Code Checkout')
		{
			steps
			{
			        git 'https://github.com/MDMujahid93/Industry-Grade-Project---Java-Project.git'
			}
		}
		
		stage('Code Compile')
		{
			steps
			{
				sh 'mvn compile'
			}
		}

		stage('Unit Test')
		{
			steps
			{
				sh 'mvn test'
			}
		}

		stage('Code packaging')
		{
			steps
			{
				sh 'mvn package'
			}
		}
   }
} 
