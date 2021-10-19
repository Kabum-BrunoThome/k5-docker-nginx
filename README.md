# k5-docker-nginx

A idéia desse repositório é facilitar pra subir os repositórios relacionados ao k5 na mesma url e mesma porta, pra compartilhar cookies e informações do localStorage

Esse repositório precisa estar no mesmo nível que os repositórios do k5

```
📦 k5
 ┣ 📂 ecommerce-frontend-checkout
 ┣ 📂 ecommerce-frontend-core
 ┣ 📂 k5-docker-nginx
```

E aí com o docker instalado e rodando na máquina é só rodar o comando ```docker-compose up --build```

E a aplicação vai estar rodando local na porta 8000
- `http://local.tst.kabum.com.br:8000`
