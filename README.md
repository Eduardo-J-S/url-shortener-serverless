# URL Shortener Serverless  
Um encurtador de URLs desenvolvido com arquitetura serverless, utilizando **AWS Lambda**, **S3** e **API Gateway**. Este projeto foi criado como forma de explorar e aplicar recursos da AWS em uma solução prática e funcional.  

## 🚀 Funcionalidades  
- **Encurtar URLs**: Gera códigos únicos para encurtar URLs longas.  
- **Redirecionamento**: Redireciona o usuário para a URL original com base no código fornecido.  
- **Validade configurável**: As URLs encurtadas expiram após o período definido.  

## 🛠️ Tecnologias utilizadas  
- **AWS Lambda**: Processamento das requisições.  
- **AWS S3**: Armazenamento dos dados das URLs encurtadas.  
- **API Gateway**: Criação de endpoints REST para interagir com o sistema.  
- **Java**: Linguagem utilizada para implementar as funções Lambda.  
- **Jackson**: Serialização e desserialização de dados JSON.  

## 🗂 Estrutura do projeto  
- **createUrlShortener**: Função Lambda responsável por gerar e salvar as URLs encurtadas no S3.  
- **redirectUrlShortener**: Função Lambda que busca as informações no S3 e redireciona o usuário.  
