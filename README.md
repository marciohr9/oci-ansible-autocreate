# Oci-ansible-autocreate
Projeto para criar um script em Ansible para criação de uma máquina free tier na estrutura OCI e instalação de alguns componentes básicos.


## Pré Requisitos

- instalação ansible.
  - [Documentação de Instalação](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)
- baixar biblioteca do oci para ansible.
  - [Documentação Biblioteca Ansible para OCI](https://oci-ansible-collection.readthedocs.io/en/latest/installation/index.html#linux-macos)
- verificar se nas suas regras de acesso IAM na OCI há um Tenacy ativo.
  - [Configuração de Regras de Acesso do IAM](https://docs.oracle.com/en-us/iaas/Content/API/SDKDocs/ansiblegetstarted.htm#configureAuth)
- Instalar a SDK do OCI para python.
  - [Link para a instalação via Pypi](https://pypi.org/project/oci/)
  - [Link para a lista oficial de configurações](https://docs.oracle.com/en-us/iaas/Content/API/Concepts/sdkconfig.htm)
  - [Link para a configuração com Python](https://docs.oracle.com/en-us/iaas/tools/python/2.90.0/configuration.html)
  - Após a instalação executar o comando `oci setup config` para iniciar a configuração da sua conta no sdk.
  - As informações do seu "USER OCID" e "Tenancy OCID" visite sua conta cloud.
  - depois disso adicione sua chave publica criada a sua conta OCI [Link para o tutorial](https://docs.oracle.com/pt-br/iaas/Content/API/Concepts/apisigningkey.htm#How2).