# Teste de API com PostMan

## Descrição

Este repositório contém cenários de teste desenvolvidos para a API pública GoRest (https://gorest.co.in/).

## Como Executar os Testes

1. Importe a coleção de testes (LISTA_02.postman_collection.json) no PostMan ou ferramenta de sua preferência.
2. Execute as requisições.
3. Verifique os resultados e as validações conforme descrito em cada cenário.

### Pré-requisitos

Certifique-se de ter o Node.js instalado na sua máquina. Você pode baixá-lo [aqui](https://nodejs.org/).

### Passos para gerar o relatório

1. **Instalar o Newman e newman reporter htmlextra**
   Execute o seguinte comando no terminal para instalar o Newman globalmente:
   ```sh
   npm install -g newman
   npm i -g newman-reporter-htmlextra

2. **Gerar relatório**
   Execute o seguinte comando no terminal para gerar o relatório de testes:
   ```sh
   newman run 'LISTA_02.postman_collection.json' -r htmlextra
      
