pipeline
{
    agent any
    stages
    {
        stage('git checkout')
        {
            steps
            {
                  gitCheckout
                    {
                        branch: 'master', 
                        url: 'https://github.com/Parthasarathy28/cd-cdprocess.git'
                    }
                
        
            }
        }
    }
}