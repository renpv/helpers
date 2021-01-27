# helpers
-Setar alias php5.6 no CLI

`alias php56="winpty C:/wamp64/bin/php/php5.6.40/php.exe"`

Erro ao tentar acessar o banco mysql com wampserver


Atualizar as seguintes chaves no arquivo `my.ini`

```
[client]
default-character-set=utf8

[mysql]
default-character-set=utf8

[mysqld]
collation-server = utf8_unicode_ci
character-set-server = utf8
```
