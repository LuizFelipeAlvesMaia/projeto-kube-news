# Projeto kube-news

### Objetivo
O projeto Kube-news é uma aplicação escrita em NodeJS e tem como objetivo ser uma aplicação de exemplo pra trabalhar com o uso de containers.

### Configuração
Pra configurar a aplicação, é preciso ter um banco de dados Postgre e pra definir o acesso ao banco, configure as variáveis de ambiente abaixo:

DB_DATABASE => Nome do banco de dados que vai ser usado.

DB_USERNAME => Usuário do banco de dados.

DB_PASSWORD => Senha do usuário do banco de dados.

DB_HOST => Endereço do banco de dados.

### Informações importantes
Esse projeto entraga uma aplicação web usando NODE.JS, usando uma iamgem Docker desenvolvida no arquivo Dockerfile no reposiitorio. Imagem também está disponivel [aqui](https://hub.docker.com/r/luiz117/projeto-kube-news)

Esse projeto utiliza as seguintes tecnologias para ser utilizado em sua máquina

* Docker
* Kubernetes
* Mini Kube
* K3D

#### Esse projeto utiliza pipeline CI / CD com Jenkins
Caso queira ver mais sobre nossa pipeline, nosso arquivo Jenkins se econtra no repositorio acima. 
