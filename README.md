# Тестовое задание 1

>[!NOTE]
> Приложение запускается в 3 терминалах.
> Два под сервисы, один для фронтенд части, чтобы проверить работу.
> Можно было собрать под одним скриптом, но так нагляднее можно отследить работу.


## Запуск бэкенд части
```
  cd backend
  npm run dev:service1 //запускает сервис 1 (Магазины, Товары, Остатки)
  npm run dev:service2 //запускает сервис 2 (История действий с остатками)
```

## Запуск фронтенд части
```
  cd frontend
  npm run dev
```

