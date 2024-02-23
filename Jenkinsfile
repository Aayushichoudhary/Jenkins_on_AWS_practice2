Pipeline
{
  agent any
  stages
  {
    stage ("GIT")
    {
      steps
      {
        git "https://github.com/Aayushichoudhary/Jenkins_on_AWS_practice2.git"
      }
    }
    stage ("Run")
    {
      steps
      {
        sh "java demo.java"
        sh "python main.py"
      }
    }
  }
}
