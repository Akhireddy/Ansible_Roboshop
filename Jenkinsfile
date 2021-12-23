 pipeline {
  agent { label 'WORKSTATION' }

   stages {
     stage('Ansbile Playbook Run') {
       steps {
         sh 'ansible-playbook  -i inv all -u akhigcp -m ansible.builtin.ping '
        }
     }
   }
 }
