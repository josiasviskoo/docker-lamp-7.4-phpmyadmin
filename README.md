Docker com Apache, MySQL 7.4, PHPMyAdmin and PHP.

Use sempre clonando esse repositório antes de subir

```
docker-compose up -d
```

PHPMYADMIN: [http://127.0.0.1:8000](http://127.0.0.1:8000)

LOCALHOST: [http://127.0.0.1:80](http://127.0.0.1:80)

PHPMYADMIN: [http://localhost:8000](http://localhost:8000)

LOCALHOST: [http://localhost:80](http://localhost:80)

Important: o hostname é variável para acesso. Consultar diretamente no painel das variáveis em phpmyadmin

Rodando o MySQL client:

- `docker-compose exec db mysql -u root -p` 
