pipeline{

agent any
stages{
stage('Build')
{steps{
sh '/usr/share/maven clean install'
}
}
stage ('Test')
{
steps{
sh '/usr/share/maven test'
} 
}
}
}
