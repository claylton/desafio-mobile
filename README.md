# Teste Técnico Mobile BeTalent

Este é um fork  que fiz baseado no desafio-mobile [https://github.com/BeMobile/desafio-mobile](https://github.com/BeMobile/desafio-mobile).

A única difereça é o caminho das imagens, onde pego de imagens diferentes dentro do figma do teste técnico, com a finalidade de ser mais fiel ao portótipo.

### Acesso aos dados da API simulada

Para ter acesso aos dados que alimentarão o projeto, faça o seguinte:

1. caso você não tenha, instale o pacote [json-server](https://github.com/typicode/json-server);
2. clone este repositório do GitHub em sua máquina: [https://github.com/claylton/desafio-mobile/tree/main](https://github.com/claylton/desafio-mobile/tree/main);
3. entre na pasta do projeto, em sua máquina, e, por meio da linha de comando, execute o comando `json-server --watch db.json`, para consumir a API simulada;
4. inicie a estrutura e o desenvolvimento do projeto.

É necessário deixar o json-server rodando no terminal para que os dados sejam visualizados no projeto.

Caso você tenha problemas com o json-server, tente rodá-lo com `npx json-server db.json` ou 
com `yarn json-server <path>/db.json`, em que `<path>` é o caminho completo até o diretório em que o arquivo db.json está localizado. Se mesmo assim não funcionar, busque ajuda na web.
