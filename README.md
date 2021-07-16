#### Projetodevops

Trabalhando com a Ferramenta Docker. Logado no Docker Hub | Realizando a Criação de uma imagem Docker, construída com o arquivo Dockerfile.

#### Primeira parte do projeto Criação de uma imagem Ubuntu.

- Utilizando os comandos:  docker image build -t msilvaops/ubuntu-curl:v1 . e com comando
docker image ls -a  para listar as images criadas. 

Após a criação da image foi adicionada no repositório Public View do docker Hub utilizando com o comando docker push msilvaops/ubuntu-curl:v1

Realizado o Push da Image para o meu endereço Public View do docker Hub disponivel para acessar e ser utilizada com o endereço abaixo;

https://hub.docker.com/repository/docker/msilvaops/ubuntu-curl

- Conclusão: Sempre que precisar utilizar a image qualquer pessoa pode fazer o docker Pull da imagem para trabalhar basta o repositório estar no modo Public View.

#### Segunda parte do projeto construção e Deploy da aplicação para rodar em um Container Docker na Cloud. 

- Criação de uma image docker com os arquivos Node.js com a API da aplicação após realizar a construção de um Dockerfile.

Após a criação da image docker foi feito o Push para o Docker Hub onde foi adicionada no repositório Public View para realizado o Deploy do Container na nuvem pública do Azure utilizando o serviço App Service que é um serviço de aplicativos onde permitem que você crie, implante e dimensione rapidamente aplicativos da Web, móveis e API de nível empresarial executados em qualquer plataforma. Atenda aos requisitos rigorosos de desempenho, escalabilidade, segurança e conformidade ao usar uma plataforma totalmente gerenciada para realizar a manutenção da infraestrutura.

https://api-msilvaopsapiconversaov1.azurewebsites.net/api-docs/

Referencia do projeto KubeDev criador da aplicação API-CONVERSAO Node.js
