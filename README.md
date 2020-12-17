# goit_fighting_game

Students project, pure fighting game on native JavaScript with html and css and gulp:

https://goit.global/students_projects/fighting_game/

## Особенности:

1. За главной веткой main следит jenkins GO IT и при пуше и пулл реквесте в ветку сборка пересобирается и выгружается на сервер
2. Это универсальная версия игры на английском

## Особенности технические (размещение React проекта в подпапку на goit.global/folderName/folderName)

Для этого меняем фо фронте:

1. В package.json добавлем
   "homepage": "https://goit.global/students_projects/fighting_game/"

## Настройка автодеплоя с помощью jenkins ветки master нужного репозитория

1. ссылка на скрин 1:
   https://gyazo.com/9de782807ee4af0da2503898d30e486c

ссылка в Payload url:

```
http://jenkins.goit.ua/github-webhook/
```

2. ссылка на скрин 2:
   https://gyazo.com/e7cf858605021e9728d865910f3b8d8e

### Коллабораторы репозитория:

1. goitProjects - github студентческих проектов GO IT
