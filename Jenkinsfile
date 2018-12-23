pipeline
{
    agent any
    stages
    {
        stage("build code")
        {
            sh "mvn clean install package"
        }
        stage("code deploy to tomcat")
        {
            echo "code deployed"
        }
    }
}
