# Вёрстка приложения «CI/CD Server»

Приложение — это CI сервер, который работает с Git репозиторием. Параметры репозитория задаются в настройках.

Для любого из коммитов репозитория можно запустить операцию сборки. Сборка — это выполнение каких-то действий над содержимым репозитория. Результатом сборки является лог её выполнения.

CI сервер должен отображать список сборок с информацией о них. Также он должен давать возможность посмотреть лог любой сборки. Кроме того, он должен иметь возможность редактирования настроек репозитория.

## БЭМ

Правила дизайн-системы описаны в терминах методологии [БЭМ](https://ru.bem.info/methodology/key-concepts). Для обозначения сущностей интерфейса используется [соглашение по именованию](https://ru.bem.info/methodology/naming-convention).

## Старт проекта

- Склонируй репозиторий и перейди в папку проекта
- Установи модули

```
npm i
```

- Запусти проект
```
npm start
```

## Скриншоты

### Стартовый экран
![Стартовый экран](screenshots/start-screen.jpeg?raw=true)
### Настройки
![Стартовый экран](screenshots/settings.jpeg?raw=true)
### История билдов
![Стартовый экран](screenshots/build-history.jpeg?raw=true)
### Детали билда
![Стартовый экран](screenshots/build-details.jpeg?raw=true)

