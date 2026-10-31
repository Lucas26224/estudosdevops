# Semana 1: Linux básico

## Navegação
- pwd: mostra onde estou
- ls -la: lista arquivos, inclusive ocultos
- cd: troca de pasta

## Permissões
- chmod 644: dono lê e escreve, os outros só leem
- chown: troca o dono de um arquivo

## Usuários e grupos
- useradd -m -s /bin/bash nome: cria usuário
- usermod -aG grupo usuario: adiciona ao grupo (o -a é essencial)
