node
{
    stage ('Checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/imran2224/firstrepo.git']]])
    }
    stage ('Static code analysis')
    {
        echo "Static code analysis done successfully"
    }
    stage ('Build')
    {
        echo "Build done successfully"
    }
    stage ('Unit Testing')
    {
        echo "Unit Testing done successfully"
    }
    stage ('Deploy')
    {
        echo "Deploy done successfully"
    }
}
