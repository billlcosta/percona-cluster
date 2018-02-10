                                         Automatização Cluster SQL Percona
                                 ---------------------------------------------------
                                              
Script desenvolvido para automatizar a criação de um cluster SQL com Percona + Galera/XtraDB e Keepalived, utilizando três servidores. Para utilizar, siga os passos abaixo.:

* Acesse o diretório "group_vars" e altere as variáveis necessárias dentro de "all";
* Altere o arquivo hosts com as informações das máquinas que serão aplicadas os scripts;
* Execute o comando ansible-playbook -i hosts playbook.yml
