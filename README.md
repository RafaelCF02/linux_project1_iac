Desafio de Script Shell - Gerenciamento de Usuários e Diretórios
================================================================

Este é um script shell desenvolvido como parte de um desafio proposto durante o curso da [Digital Innovation One (DIO)](https://digitalinnovation.one/). O script automatiza o processo de criação de diretórios, grupos de usuários e usuários em um sistema Linux, além de definir permissões adequadas para os diretórios criados.

Funcionalidades
---------------

*   Criação de diretórios (/publico, /adm, /ven, /sec).
*   Criação de grupos de usuários (GRP\_ADM, GRP\_VEN, GRP\_SEC).
*   Criação de usuários nos grupos correspondentes.
*   Definição de senhas criptografadas para os usuários.
*   Especificação de permissões para os diretórios criados.

Requisitos
----------

Para executar este script, é necessário ter:

*   Acesso a um sistema Linux.
*   Permissões de superusuário (root) para executar comandos como `mkdir`, `groupadd`, `useradd`, `chown` e `chmod`.
*   O comando `openssl` instalado para criar senhas criptografadas.

Como usar
---------

1.  Clone este repositório para o seu sistema:

```git clone https://github.com/RafaelCF02/linux_project1_iac.git```

2.  Navegue até o diretório do projeto:

```cd linux_project1_iac```

3.  Execute o script:

`./criar_contas.sh`


Notas
-----

*   Este script foi desenvolvido como parte de um desafio educacional e pode ser usado para aprendizado e prática.
