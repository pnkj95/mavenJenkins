pipeline
{
    agent any

    stages 
    {
        stage('Build') 
        {
            steps 
            {
                echo 'Building the App'
            }
        }
        stage('Test') 
        {
            steps 
            {
                echo 'Testting the App'
            }
        }
        stage('Deploy') 
        {
            steps 
            {
                echo 'Deploying the App'
            }
        }
    }
    post{
        always{
            emailext body: 'Test Body', subject: 'Test Subject', to: 'pankajpathakipem@gmail.com'
        }
    }
}

