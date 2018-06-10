Instalar o `nvm` no Ubuntu e sistemas baseados.
Este primeiro comando faz o download do arquivo de instalação para o seu diretório /home
`wget https://raw.githubusercontent.com/creationix/nvm/v0.33.0/install.sh` -- Observe as atualizações da versão.
Habilite seu arquivo de instalação para que seja executado.
`sudo chmod +x install.sh`
Agora sim, instale
`sudo ./install.sh`
Verifica as versões disponíveis
`nvm ls-remote`
Instale a versão que você precisa.
`nvm install 8`
Se ocorrer problema de permissão negada, você precisa alterar as permissões da pasta oculta `/home/.nvm`

instale no diretório do seu projeto: `npm install`.

Verificar versão instalada do nvm `nvm --version`.
Verificar versão instalada do npm `npm -v`.
Verificar versão instalada do node `node -v`.
