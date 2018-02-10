                                                        Scripts Ansible.
                                              ------------------------------------
                                              
Este repositório contém algumas receitas ansible para automatizar algumas tarefas de instalações de serviços/aplicações. Para utilizar, siga os passos.:

* Acesse o diretório "group_vars" e altere as variáveis necessárias dentro de "all";
* Altere o arquivo hosts com as informações das máquinas que serão aplicadas os scripts;
* Descomente as entradas que deseja utilizar em playbook.yml;
* Execute o comando ansible-playbook -i hosts playbook.yml
