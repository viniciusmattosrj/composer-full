# Composer Full

 - <a href="https://www.youtube.com/watch?v=_n57YVUVT2A&list=PLVSNL1PHDWvSrVzXyKxBc5cPM4sU7-c2T">Curso Composer</a> - Carlos Ferreira da Especializa TI


## Requerimentos

Install <a href="https://docs.docker.com/install/">Docker</a>

Install <a href="https://docs.docker.com/compose/install/">docker-compose</a>


## Tecnologias utilizadas:

 - PHP >= 7.1
 - Docker


## Instalação
Realizar o git clone do projeto
```bash
git clone git@github.com:viniciusmattosrj/composer-full.git
```

Entre pelo terminal na pasta do projeto e rode:
```
cp ./docker-compose-example.php  ./docker-compose.php
```

Agora suba o servidor:
```
docker-compose up -d
```

Em outra aba do terminal se conecte no container do php e inicie um servidor built in do PHP
```
docker exec -it php bash
php -S 10.11.0.2:8008 -t public
```

No browser digite http://10.11.0.2:8008

## Contribuições
Caso identifique pontos
que possam ser aprimorados envie o seu PR. ;-)


## License
[MIT](https://choosealicense.com/licenses/mit/)
