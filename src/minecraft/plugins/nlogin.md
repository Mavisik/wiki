---
authors: 
  - FlashYan123
---

# nLogin

nLogin - это плагин для сервера Minecraft, который предоставляет механизм аутентификации и управления учетными записями игроков на сервере. Он позволяет администраторам контролировать доступ к серверу, а также предоставляет игрокам возможность создавать и управлять своими учетными записями.

## Установка

1. Скачайте плагин [nLogin с официального сайта](https://www.nickuc.com/en/#plugins).
2. Переместите скачанный файл плагина в папку ~/plugins вашего сервера.
3. Перезапустите сервер, чтобы плагин был загружен.

## Конфигурация

1. После установки плагина в папке ~/plugins вы увидите файл "config.yml".
2. Откройте файл конфигурации.
3. В файле конфигурации вы найдете следующие параметры:

   - `enable-registration`: Определяет, разрешена ли регистрация новых учетных записей. Значение по умолчанию: true.
   - `enable-password-recovery`: Определяет, разрешено ли восстановление утерянных паролей. Значение по умолчанию: true.
   - `default-group`: Определяет группу, к которой принадлежит новый зарегистрированный игрок. Значение по умолчанию: default.
   - `login-attempts`: Определяет максимальное количество попыток входа до временной блокировки учетной записи. Значение по умолчанию: 3.
   - `lock-time`: Определяет время блокировки учетной записи (в минутах) после достижения максимального количества попыток входа. Значение по умолчанию: 5.

4. Измените значения параметров по вашему усмотрению и сохраните файл конфигурации.

## Команды и права

nLogin предоставляет несколько команд для администрирования учетных записей и управления доступом к серверу:

- `/register <пароль> <подтверждение>`: Регистрирует новую учетную запись на сервере.
- `/login <пароль>`: Выполняет вход в игру с использованием учетных данных.
- `/changepassword <старый_пароль> <новый_пароль> <подтверждение>`: Изменяет пароль для текущего пользователя.
- `/recoverpassword <игровое_имя>`: Отправляет на почту письмо со сбросом пароля.
- `/lockaccount <игровое_имя>`: Блокирует учетную запись игрока.
- `/unlockaccount <игровое_имя>`: Разблокирует заблокированную учетную запись игрока.
- `/nlogin reload`: Перезагружает конфигурацию плагина.

Для использования этих команд игроки должны иметь соответствующие права доступа:

- `nlogin.register`: Разрешает игрокам регистрировать новые учетные записи.
- `nlogin.login`: Разрешает игрокам входить на сервер.
- `nlogin.changepassword`: Разрешает игрокам менять свои пароли.
- `nlogin.recoverpassword`: Разрешает игрокам восстанавливать утерянные пароли.
- `nlogin.lockaccount`: Разрешает администраторам блокировать учетные записи игроков.
- `nlogin.unlockaccount`: Разрешает администраторам разблокировать учетные записи игроков.
- `nlogin.reload`: Разрешает администраторам перезагружать конфигурацию плагина.