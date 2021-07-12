node('master') 
{
    stage('Continuous Download_raju') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_raju') 
	{
    sh label: '', script: 'mvn package'
	}
}
