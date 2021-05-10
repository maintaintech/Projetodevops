# Projetodevops

Trabalhando com a Ferramenta Docker. Logado no Docker Hub | Realizando a Criação Docker image com o arquivo Dockerfile

Utilizando os comandos:  docker image build -t msilvaops/ubuntu-curl:v1 . e com comando
docker image ls -a  para listar as images criadas. 

Após a criação da image foi adicionada no repositório Public View do docker Hub utilizando com o comando docker push msilvaops/ubuntu-curl:v1

Realizado o Push da Image para o meu endereço Public View do docker Hub disponivel para acessar e ser utilizada com o endereço abaixo;

https://hub.docker.com/repository/docker/msilvaops/ubuntu-curl

Conclusão: Sempre que precisar utilizar a image qualquer pessoa pode fazer o docker Pull da imagem para trabalhar basta o repositório estar no modo Public View.

Segunda parte do projeto criação de uma image docker com os arquivos Node.js 

URL da API da aplicação em Node.js criada com a image docker e realizado o deploy na nuvem publica App Azure.

https://api-msilvaopsapiconversaov1.azurewebsites.net/api-docs/

Referencia do projeto KubeDev criador da aplicação API-CONVERSAO Node.js