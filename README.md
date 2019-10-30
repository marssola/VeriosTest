# VeriosTest
Projeto para o teste da Vérios

## Instalação
```bash
$ yarn install
```
### Arquivo de configuração das moedas disponíveis e produtos
```bash
./src/config/data.json
```

## Executar os testes
```bash
$ yarn test
```

# Executar o CLI
```bash
$ node src/index.js
```

## Opções
* -a, --all-products    Exibie todos os produtos
* -i, --product <item>  Exibe o produto com base no índice informado <item> = índice
* -p, --pay <value>     Payment value
* -b, --buy               Comprar o produto. Este opção depende de informar o produto (-i, --product) a ser comprada e o valor a ser inserido (-p, --pay)
  
## Exemplo

**Exibir todos os produtos**
```bash
$ node src/index.js --all-products
```

**Exibir o produto com base no índice**
```bash
$ node src/index.js --product 0
```

**Comprar um produto**
```bash
$ node src/index.js --product 0 --pay 5.00 --buy
```
