# Gulliver Traveller

Agora podemos buildar o container com:

`docker-compose build`

E subir a API com o comando:

`docker-compose up`

Da mesma forma caso queira parar os servicos use:

`docker-compose down`

Com a API rodando em um terminal abra outra janela e chame a API, mas dessa vez usando a porta 80, como mapeamos no compose:

```bash
curl -H "Content-Type: application/json" localhost -v
```
