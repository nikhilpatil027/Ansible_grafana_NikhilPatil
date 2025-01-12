pipeline
{ 
    agent any
    stages
    {
        stage("Execute grafana"){
            steps{
                sh "sudo ansible-playbook grafana_install.yml"
                
            }
            
        }
    }
}
