### Sobre

Este template Docker é a sua solução para criar aplicações WordPress de alto desempenho. Ele fornece o ambiente isolado e configurável que você precisa para trabalhar com integração RESTful e desenvolver plugins customizados com eficiência.

### Ferramentas:
- redis (lastest)
- wordpress
- mariadb 10.11

### Como usar:
**Clone o repositório**
```bash
git clone 'url'
```

**Copie o .env.example e crie suas credenciais**
```bash
cp .env.example .env
```

**Construa a aplicação**
```bash
docker compose -f docker-compose.dev.yaml up -d --build
```

### </> Desenvolva e seja feliz </>