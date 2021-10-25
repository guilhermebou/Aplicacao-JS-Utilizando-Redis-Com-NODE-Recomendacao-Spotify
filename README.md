# Aplica-o-JS-utilizando-Redis-com-NODE---Recomenda-o-Spotify
Aplicação JS utilizando Redis com NODE - Recomendação Spotify \\ Trabalho UFU 2021-2 GSI520  BD1 

-> Chocolatey 0.11.2 <-
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))

->npm 6.14.15<-
choco install -y --force nodejs

->yarn 1.12.17 <-
npm install --global yarn

-> ioredis 4.28 <-
yarn add ioredis

-> Docker 20.10.8 <-
ativar hyper-v e WSL 
painel de controle/ativar e desativar recursos windows/...
https://docs.docker.com/desktop/windows/install/ 

-> imagem redis 6.2.6 <-
https://hub.docker.com/_/redis

-> cmd <-
	
		docker run --name redis -p 6379:6379 -d redis
		verificacao run : dcoker ps
		verificacao images : docker images
	{
	
-> Execucao aplicacao <-

"Yarn start" no cmd dentro do diretorio 





https://docs.docker.com/desktop/windows/install/ 
https://hub.docker.com/_/redis
https://yarnpkg.com/getting-started/install
https://docs.npmjs.com/cli/v7/commands/npm-install
https://chocolatey.org/install
https://developer.spotify.com/console/get-recommendations/


https://www.youtube.com/watch?v=tU3oU0jkKZ4&t=9s
