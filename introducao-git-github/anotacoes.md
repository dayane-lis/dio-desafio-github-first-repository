### Chave SSH

Para criar uma chave SSH no terminal (Powershell ou Git Bash), digitamos o seguinte código:
ssh-keygen -t ed25519 -C <e-mail>

Isso irá gerar uma imagem SHA. Feito isso, vamos entrar na pasta .ssh:
cd /c/users/<usuário>/.ssh

Confirmamos os arquivos salvos no diretório através do comando ls (ou dir no Powershell).
