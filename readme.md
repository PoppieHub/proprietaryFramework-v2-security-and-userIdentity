# Второй собственный mvc framework. Безопасность и идентификация пользователя. Сбор информации о приложении.

---

### Конфигурационные файлы:
Конфигурация подключения к бд осуществляется в `config/db_config.php`.
Конфигурация связи маршрута с акшеном в контроллере `app/app_routes.php`.

### Установка БД.
Для установки импортируйте файл `module27.sql` из директории `db` в базу данных.


- В БД записаны пользователи (пароль у них: ***password*** или ***123456***):
- При авторизации они попадают на страницу "Success", которую могут открыть только авторизованные пользователи. На этой странице один абзац текста и одну картинку. Текст виден всем авторизованным пользователям, картинка — только пользователям с ролью «пользователь ВК»
- Неудачные попытки входа записываются в файл "/access_log.log"

LICENSE: [MIT](./license.md)

---

AUTHOR: PoppieHub@GitHub
