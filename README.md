[![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/Watson-Sei/Tests4GeeksBlog-DRF-Tutorial) 

# Tests4GeeksBlog-DRF-Tutorial
https://tests4geeks.com/blog/django-rest-framework-tutorial/


## config/settings.py
```
DATABASES = {
    'default':{
        'ENGINE':'django.db.backends.mysql',
        'NAME':'django_docker',
        'USER':'root',
        'HOST':'db',
        'POST':33306
    }
}
```

## 起動
``` 
docker-composes up 
```