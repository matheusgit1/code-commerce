## Code Commerce

Este projeto é uma parte de um projeto maior, um ecommerce baseado em microserviços.

![Arquitetura](https://github.com/matheusgit1/orders-api/blob/main/assets/arq%20geral.png)

Este repositório se refere ao frontend, onde todas as ações e iterações podem ser feitas.

para execução local

```bash
npm run dev
```

Os demais serviços que compoem o projeto podem ser baixados em cada um dos respectivos repositórios, sendo eles:

api de compras: https://github.com/matheusgit1/orders-api

api de produtos: https://github.com/matheusgit1/products-go-api

api de pagamentos: https://github.com/matheusgit1/payments-go-api

frontend:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Abra seu naveador em [http://localhost:3000](http://localhost:3000)

## Arquitetura Implementada

![Arquitetura](https://github.com/matheusgit1/orders-api/blob/main/assets/arq%20geral.png)

Este serviço se refere ao frontend

Em linhas gerais: uma api lista os produtos, o cliente pode executar suas comprar e ordem de compra é gerada e enviada para uma fila de processamento, o rabbitmq, essas messagens por sua vez seram tratadas por um serviço apartada, api de pagamentos.

Nesse cenário temos um projeto baseado em microserviço que funcionam de forma desacoplada, em caso

Cenário:

1 - caso a api de produtos esteja fora, as ordems de compra continuaram a ser processadas, sem perda de vendas.

2 - Caso a api de pagamentos esteja fora, as ordems serão salvas até o sistema ser restabelecido.

## Execução

Para testar o projeto localmente, clone os demais items que compõe esse projeto executeos localmente

**Cada repositório com sua própria documentação**

api de compras: https://github.com/matheusgit1/orders-api

api de produtos: https://github.com/matheusgit1/products-go-api

api de pagamentos: https://github.com/matheusgit1/payments-go-api

frontend:

## Stack utilizada

Nextjs, Typescrip, Yup, Hook Form

## Testes unitário

TODO

## Arquitetura implementada

### Arquitetura geral do projeto

![Arquitetura](https://github.com/matheusgit1/orders-api/blob/main/assets/arq%20geral.png)

## Sobre o Autor

Eu sou uma pessoa desenvolvedora full-stack, técnico em administração, engenheiro de automação em formação, e cientista de dados em formação. Sempre busco por excelência e entregar o máximo com a maior qualidade, sem claro, deixar de lado boas práticas.

Atualmente sou desenvolvedor full stack júnior da área de desenvolvimento de softwares, mirando senioridades cada vez mais altas.

Tenho habilidades com as stacks mais modernas, como :nodeJS, typeScript, css, html, nestJs, NextJs, aws-cloud, bancos de dados não relacionais como mongodb e redis, bancos de dados relacionais como MySql, postgres, docker, testes unitários e de integração. Atuando também em diferentes setores, como educação e telecomunicação.

## Quer entrar em contato com o desenvolvedor?

🪜 Instagram (sempre respondo): @ap_matheus

📱 Telefone e whatsapp: 55 27 997822665

📫 Email: pereira.matheusalves@gmail.com

🔗 Linkedin: https://www.linkedin.com/in/matheus-alves-pereira-4b3781222/
