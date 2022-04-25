node('Slave2_lab') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build Loans') 
	{
    sh label: '', script: 'mvn package'
	}
}
