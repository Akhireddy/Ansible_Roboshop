 pipeline {
  agent { label 'WORKSTATION' }

   stages {
     stage('Ansbile Playbook Run') {
       steps {
         sh 'ansible -i inv all -u akhigcp -m ansible.builtin.ping '
        }
     }
   }
 }
