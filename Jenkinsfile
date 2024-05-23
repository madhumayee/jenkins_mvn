Pipeline
{
tools{
          jdk ‘JAVA_HOME’
          maven ‘M2_HOME’
        }
      agent  any
           stages{
           stage (“checkout”)
         {
        steps{
             git 'https://github.com/Soumyajit-Rout/jenkins_mvn.git'
        }
  stage (“compile”)
{
steps{
sh  ‘mvn compile’
}
}
}
}
