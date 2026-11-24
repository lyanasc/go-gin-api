# Go Gin API

API de exemplo em Go com o framework Gin. Expõe uma rota de status e uma rota que retorna uma mensagem em JSON.

## Executar localmente

Com Go 1.26.1 ou compatível instalado, execute o comando na raiz do projeto.

~~~bash
go run .
~~~

O servidor inicia na porta 8080.

| Rota | Resposta |
| --- | --- |
| GET /health | {"status":"ok"} |
| GET /hello | {"message":"Hello from Gin"} |

~~~bash
curl http://localhost:8080/health
curl http://localhost:8080/hello
~~~
