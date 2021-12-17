# Ansible_Roboshop
- name: Demo on simple playbook
  hosts: all
  tasks:
    - name: Task1
      ansible.builtin.debug:
      msg: 'Hello from Playbook Play'
    - name: Task2
      ansible.builtin.debug:
      msg: "Hello from Playbook Play Task2"