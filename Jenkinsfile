pipeline
{ 
    agent { label 'slave2' }
    stages
    {
        stage("Execute grafana"){
            steps{
                sh "sudo ansible-playbook grafana_install.yml"
                
            }
            
        }
    }
}
