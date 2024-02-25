### Запуск

Перейти в директорию с проектом и выполнить команду:
```
kubectl apply -f ./
```

### curl:

curl http://arch.homework/health  
curl http://arch.homework/otusapp/alex/health

Запуск тестов:
```
newman run ./tests/postmanCollection.json
```