# README - Ferramentas DEvOPs

Este projeto é para estudo de ferramentas DevOps utilizando a máquina local.

Utilizando o Vagrant para criar uma VM Ubuntu no VirtualBox e a Gerência de Configuração fica por conta do
Ansible.

O arquivo Vagrantfile é usado pelo Vagrant para criar VM no VirtualBox, provisionar memória, CPU e indicar qual será gerenciador de configuração a ser utilizado.
  
O arquivo hosts indica qual máquina sera atingida pelo Ansible e no script webserver.yml informamos quais as alterações serã realizadas na máquina.
