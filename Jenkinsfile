node('master') 
{
    stage('Continuous Download_launch') 
	{
    git 'https://github.com/sunildevops77/Jenkins_multiBranch24.git'
	}
    stage('Continuous Build_launch') 
	{
    sh 'mvn package'
	}
    
}

