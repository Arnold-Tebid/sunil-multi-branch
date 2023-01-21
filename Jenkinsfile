node('master') 
{
    stage('Continuous Download_loans') 
	{
    git 'https://github.com/sunildevops77/Jenkins_multiBranch24.git'
	}
    stage('Continuous Build_loans') 
	{
    sh 'mvn package'
	}
    
}

