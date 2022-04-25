node('master') 
{
    stage('Continuous Download Master') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build Master') 
	{
    sh label: '', script: 'mvn package'
	}
}
