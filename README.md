# estudos-django
Mudando a porta

Por padrão, o runservercomando inicia o servidor de desenvolvimento no IP interno na porta 8000.

Se você deseja alterar a porta do servidor, passe-a como um argumento de linha de comando. Por exemplo, este comando inicia o servidor na porta 8080:

``` bash
python manage.py runserver 8080
```

Caso queira alterar o IP do servidor, passe junto com a porta. Por exemplo, para ouvir todos os IPs públicos disponíveis (o que é útil se você estiver executando o Vagrant ou quiser exibir seu trabalho em outros computadores da rede), use:
``` bash
python manage.py runserver 0.0.0.0:8000
```
