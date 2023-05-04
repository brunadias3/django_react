# Manual
 
 ## No Windows

Para rodar o projeto:

Certifique-se de ter o python instalado.

1. Após clonar o projeto, entre na pasta django_react/myproject com o comando:
```cd myproject```

2. Em seguida, instale o Django com o comando:
```pip install Django```

3. E por fim, rode o projeto com o comando:
```python manage.py runserver```

## No Debian

Para rodar o projeto:

1. Atualize seus pacote com: 
```apt-get update```

2. Instale o python e o pip (gerenciador de pacotes do python) com:
```apt-get install python3 python3-pip tree -y```

3. Em seguida, instale o django com:
```pip3 install Django```

4. Abra a pasta opt com:
```cd /opt```

5. Para clonar o projeto é necessário que tenhamos o git instalado na máquina. Podemos instalar com:
```apt-get install git```

6. Hora de Clonar! Clone o projeto com:
```git clone https://github.com/brunadias3/django_react.git```

7. Entre no repositorio com:
```cd django_react```

8. Entre na pasta do projeto com:
```cd myproject```

9. Sete a aplicação com o seu respectivo IP, no arquivo settings.py:
```ALLOWED_HOSTS = ['SEU_IP']```

10. Em seguida, é só rodar o projeto com:
```python3 manage.py runserver 0.0.0.0:8000```
