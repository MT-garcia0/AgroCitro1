 Membros: MATHEUS GARCIA DE OLIVEIRA
 
PREDRO HENRIQUE FERRACIOLI MARQUES

ERIC FERNANDO FERREIRA RODRIGUES

MARIA ISABELLA SILVA MACHADO

# AgroCitro
## Sobre: Um sistema de cadastro e monitoramento de plantios.  
Ele permite registrar informações sobre **variedade**, **quantidade**, **data** e **localização** entre outros, ajudando a manter o controle sustentável da produção. 
### 1- Dependêsncias utilizadas: npm init -y isso vai criar o arquivo package.json, cor, nodemom e  npm install express mysql2 express, → cria o servidor web e mysql2 → conecta ao MySQL.
### 2- Criar o servidor no seu editor como o vscode e crie o arquivo server.js dentro da pasta.


Ex: const express = require('express');
const app = express();

app.get('/', (req, res) => {
  res.send(' AgroCitro - Servidor rodando!');
});

app.listen(4000, () => {
  console.log('Servidor rodando em http://localhost:4000 ');
});

### 3- Variáveis de ambiente
DB_HOST → endereço do servidor MySQL (localhost).

DB_USER → usuário configurado no MySQL.

DB_PASS → senha desse usuário (se não tiver senha, deixar vazio).

DB_NAME → nome do banco de dados (agro_citro).

PORT → porta em que o servidor Express vai rodar.
### 4- Comandos de inicialização
Passo 2 – Comandos no terminal: 
npm start

### 5- Execução dos Testes
Verifique se o npm start roda seu servidor sem erros.

Veja se no terminal há uma mensagem feita por você,para confirmar que tudo está de acordo.
"Servidor rodando na porta 3000"

Teste o HTML e CSS no navegador, se tudo está conforme os códigos, o layout, imagens e recursos são carregador normalmente.
Se todos os itens acima estiverem certos, seu programa está funcionando!







