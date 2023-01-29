
# Venom Bot com OpenAI

Este projeto é um exemplo de como criar um bot de WhatsApp utilizando a biblioteca [Venom-Bot](https://github.com/hugomelo/venom-bot) e integrando com a API do OpenAI para gerar respostas automatizadas.

## Requisitos

-   Node.js
-   Um número de telefone válido para criar o bot
-   Uma chave de API válida do OpenAI

## Instalação

1.  Faça o clone do repositório

bashCopy code

`git clone https://github.com/jorgeluis-dev/zap-chatgpt-venombot-integrate.git` 

2.  Instale as dependências

Copy code

`npm install` 

3.  Adicione as informações de autenticação no arquivo `.env`

makefileCopy code

`ORGANIZATION_ID=SUA_ORGANIZATION_ID
OPENAI_KEY=SUA_API_KEY
BOT_NUMBER=SEU_NUMERO_TELEFONE` 

4.  Execute o projeto

sqlCopy code

`npm start` 

## Comandos

-   `/bot` seguido de uma pergunta: Envia uma resposta gerada pela API do OpenAI usando o modelo "text-davinci-003".
-   `/img` seguido de uma descrição: Envia uma imagem gerada pela API do OpenAI usando o modelo DALL-E.

## Nota

Este projeto é apenas um exemplo de como utilizar a biblioteca Venom-Bot e a API do OpenAI. Ele deve ser utilizado como base para desenvolvimento de novas funcionalidades.
