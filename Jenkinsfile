pipeline
{ 
    agent { label 'server1' }
    stages
    {
        stage("Execute grafana"){
            steps{
                sh "sudo ansible-playbook grafana_install.yml"
                
            }
            
        }
    }
}
