# project
Django Project

## Requirements
1. https://apps.microsoft.com/store/detail/windows-terminal/9N0DX20HK701?hl=en-us&gl=us
2. https://learn.microsoft.com/en-us/windows/wsl/install
3. https://www.docker.com/products/docker-desktop/

## Commands
Commands to be run from a WSL Ubuntu command line

Bring up app
```
docker-compose up
```

Tear down app
```
docker-compose down
```

Create Super User
```
docker-compose exec web python manage.py createsuperuser
```

Make Migrations
```
docker-compose exec web python manage.py makemigrations
```

Migrate
```
docker-compose exec web python manage.py migrate
```

Run Tests
```
docker-compose exec web python manage.py test
```