# Задача 1


### Сборка образа


```
docker build --tag my_nginx:1.0 .
```


### Запуск контейнера


```
docker run -d -p 7777:80 --rm my_nginx:1.0
```

