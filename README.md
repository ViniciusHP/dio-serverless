<h1 align="center">
  Dio-Serverless
</h1>

<h4 align="center">Status: ✔ Concluído</h4>

---

<p align="center">
 <a href="#user-content-sobre-o-projeto">Sobre o projeto</a> |
 <a href="#user-content-executando-o-projeto">Executando o projeto</a> |
 <a href="#user-content-tecnologias">Tecnologias</a>
</p>

---

## **Sobre o projeto**

Utilização do Serverless Framework para Infraestrutura como Código (IaC) construído no bootcamp [GFT Java & AWS Developer](https://digitalinnovation.one/bootcamps/gft-java-aws-developer?utm_source=https://digitalinnovation.one/bootcamps/gft-java-aws-developer%3Futm_source%3Dsm-organico-fb-ig-bc-java-serverless%2B-gft%26utm_medium%3Dorganic%26utm_campaign%3Dgft) com a [Digital Innovation One](https://digitalinnovation.one/) e o [Cassiano Peres](https://www.linkedin.com/in/cassiano-ricardo-de-oliveira-peres-41bb86100/). [Link para o repositório original.](https://github.com/cassianobrexbit/dio-live-serverless-2907)

## **Executando o projeto**

### Pré-requisitos
Antes de começar, é necessário você já tenha as ferramentas [Node.js](https://nodejs.org/en/), [Git](https://git-scm.com/) e [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-welcome.html) instaladas.

Também é necessário as credenciais AWS, para isso crie um usuário:

AWS Management Console => IAM Dashboard => Create New User => <Nome do Usuário> => Permissions Administrator Access => Programmatic Access => Dowload Keys

Após a criação do usuário adicione as credenciais:

``$ aws configure <adicione-as-credenciais-aqui>``

### Instruções de execução do projeto
```bash
# Clone este repositório
$ git clone https://github.com/ViniciusHP/dio-serverless.git

# Acesse a pasta deste projeto por meio do terminal
$ cd dio-serverless

# Instale as dependências deste projeto
$ npm install

# Fazer deploy para nuvem
$ serverless deploy -v
```

## **Tecnologias**

Este projeto foi construído com as seguintes ferramentas:

- **[Serverless Framework](https://www.serverless.com/)**