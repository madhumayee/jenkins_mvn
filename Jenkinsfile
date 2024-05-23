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
        Steps{
             git 'https://github.com/Soumyajit-Rout/jenkins_mvn.git'
        }
  Stage (“compile”)
{
Steps{
Sh  ‘mvn compile’
}
}
}
}
