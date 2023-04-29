pipeline
{
    agent any
    stages
    {
        stage('git checkout')
        {
            steps
            {
                script 
                {
                    git credentialsId: '6080d85c-2dec-40ad-8125-67e574c6123a', url: 'git@github.com:Parthasarathy28/CD-CD_java_app.git'
                }
            }
        }
    }
}