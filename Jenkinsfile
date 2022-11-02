node {
    stage('Clone Repo') { 
        
        git 'https://github.com/marlincia/Test.git'

    }
    stage('Ansible Running') {
    
        sh 'ansible-playbook -i inventory showver.yaml' 
    }
}
