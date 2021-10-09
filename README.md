# k5-docker-nginx

A idéia desse repositório é facilitar pra subir os repositórios relacionados ao k5 na mesma url e mesma porta, pra compartilhar cookies e informações do localStorage

Os arquivos:
- `docker-compose.yml`
- `nginx.conf`

Precisam estar na raiz onde os repositórios do k5 estão, por exemplo:

```
📦 k5
 ┣ 📂 ecommerce-frontend-checkout
 ┣ 📂 ecommerce-frontend-core
 ┣ 📜 docker-compose.yml
 ┗ 📜 nginx.conf
```

E aí com o docker instalado e rodando na máquina é só rodar o comando ```docker-compose up --build```

E a aplicação vai estar rodando local na porta 8000
- `http://local.tst.kabum.com.br:8000`
