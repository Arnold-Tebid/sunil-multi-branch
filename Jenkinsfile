node('master') 
{
    stage('Continuous Download_loans') 
	{
    git 'https://github.com/Arnold-Tebid/sunil-multi-branch.git'
	}
    stage('Continuous Build_loans') 
	{
    sh 'mvn package'
	}
    
}

