# Публикация поста с изображением в 3 соц сети (вк/фб/телеграм)

## Требования
  
  * python3.5
  * установка зависимостей
  ```pip install -r requirements.txt```
  * иметь учетные записи в данных сетях
  * группу вк/фб, канал/бота в телеграмме
  * получить токен vk c правами(scope):photos, groups, wall, offline - https://vk.com/dev/implicit_flow_user
    узнать id группы/альбома группы.
  * создать бота тг/получить токен - https://smmplanner.com/blog/otlozhennyj-posting-v-telegram/
  * создать группу, приложение в фб.
    получить токен с правом publish_to_groups - https://developers.facebook.com/docs/graph-api/explorer/
  * записать .env файл:
  ```
vk_login=...
vk_token=...
vk_album_id=...
vk_group_id=...
tg_token=...
tg_chat_id=...
fb_token=...
fb_group_id=...
  ```


  
  Пример:
```bash
$ python main.py -t <путь до тхт с постом> -i <путь до изображения>

```


## Цель проекта
Код написан в учебных целях. Учебный курс для веб-разработчиков - [dvmn.org](https://dvmn.org)
