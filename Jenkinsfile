node {
    stage('Clone Repo') { 
        
        git 'https://github.com/marlincia/NetOps.git'

    }
    stage('Ansible Running') {
    
        sh 'ansible-playbook -i inventory showver.yaml' 
    }
}
