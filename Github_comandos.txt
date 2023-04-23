## Github
**SSH**
ssh-keygen -t ed25519 -C "email"
cat id_ed25519.pub
Copie essa chave e leve para o GituHub Profile - SSH Keys

**Git Clone**
Consiste em baixar o codigo do GitHub para sua maquina local. 
Escolha o projeto e clique em Code SSH e copie. Na pasta do seu terminal digite:
git clone <Paste do git SSH que copiou>
Pode ocorrer o seguinte erro:
The authenticity of host 'github.com (um IP)' can't be established.
Para acertar esse problema faca:
ssh-keyscan github.com >> ~/.ssh/known_hosts

**Subir codigo**
git add.
git commit -m "texto explicativo"
git push origin main

