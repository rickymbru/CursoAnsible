# CursoAnsible
Repositório com os arquivos utilizados no curso de Ansible.

O Conteúdo deste repositório foi utilizado para a ministração do curso de Ansible. 
O curso completo pode ser acessado no seguinte link: https://www.youtube.com/watch?v=Os0Uo5VXxNU&list=PLORF-y_edVoDQnky9u2OgyrfirE1dhutX

## ad hoc
`` ansible ol -m yum -a "name=curl state=present" -became ``

## Facts
`` ansible all -m setup ``
``ansible all -m setup -a "filter=ansible_distribution" ``
``ansible all -m setup -a "filter=ansible_hostname" ``
``ansible all -m setup -a "filter=ansible_memtotal_mb" ``

## instalar varivel Python em ansible.cfg
interpreter_python = /usr/bin/python

## Atualizar o ansbile
`` sudo apt-add-repository ppa:ansible/ansible ``
`` sudo apt-get update ``
`` sudo apt-get install ansible ``


