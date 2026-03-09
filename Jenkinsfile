pipeline 
{
    agent any
	triggers 
	{
        	githubPush()
        	cron('H/10 * * * *')
    	}

    	stages 
	{
        	stage('Build') 
		{
            		steps 
			{
                		echo 'Building project from GitHub'
            		}
        	}

        	stage('Test') 
		{
             		steps 
			{
                		echo 'Running tests'
            		}
        	}
    }
}