# sshbfPy
Brute force SSH script in python
#############sshbf#############
############by=DKZ#############

O programa ira testar todas as senhas possiveis e caso encontre alguma senha compativel ira mostrar e gerar um arquivo (credentials.txt) contendo todas as senhas que foram compativeis

ATENÇÃO

requisitos:

python 3 instalado
biblioteca paramiko instalada
biblioteca colorama instalada

modo de usar:
SSH Bruteforce Python script
-host - Hostname ou Endereço IP do Servidor SSH para o bruteforce
-P - Arquivo que contem uma lista de senhas em cada linha
-U - Arquivo que contem uma lista de usuários em cada linha
-u - Nome de usuário caso quera inserir somente um username

exemplo de uso:
Ir na pasta do programa pelo terminal e executar o comando conforme os exemplos:

   exemplo 1: python sshbf.py -host 192.168.0.1 -u admin -P pass.txt
   exemplo 2: python sshbf.py -host 192.168.0.1 -U users.txt -P pass.txt
