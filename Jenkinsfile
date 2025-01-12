pipeline
{ 
    agent { label 'server2' }
    stages
    {
        stage("Execute grafana"){
            steps{
                sh "sudo ansible-playbook grafana_install.yml"
                
            }
            
        }
    }
}
