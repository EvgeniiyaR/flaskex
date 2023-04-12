**Тестовое задание на DevOps-практикум**

https://github.com/anfederico/Flaskex

Задание:
 * Запустить локально, исправить ошибки;
 * Упаковать в docker;
 * Запустить упакованное приложение через docker-compose.

Выполнение:

При локальном запуске: 
  * Ошибка: "AttributeError: module 'wtforms.validators' has no attribute 'required'"
  * Решение: scripts/forms.py в классе LoginForm заменила validators.required() => validators.DataRequired() в переменных username, password
