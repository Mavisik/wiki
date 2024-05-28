---
authors:
  - FlashYan123
---

# Geyser

Geyser - плагин для обеспечения поддержки подключения к серверу Minecraft с устройств, работающих на других платформах, таких как Bedrock Edition (Pocket Edition, Xbox, PlayStation и другие).

## Установка

1. Скачайте последнюю версию плагина [Geyser](https://geysermc.org/download)
2. Переместите скачанный файл плагина в ~/plugins.
3. Перезапустите сервер Minecraft, чтобы плагин Geyser загрузился.

## Конфигурация

1. После установки плагина Geyser в папке ~/plugins сервера Minecraft появится папка с именем "Geyser". В этой папке находятся файлы конфигурации.
2. Откройте файл "config.yml".
3. Внесите необходимые изменения в файл конфигурации в соответствии с вашими предпочтениями. В файле содержатся различные параметры, которые можно настроить, включая порт сервера **(порт открывается во вкладке Network, и после этого его можно внести в конфигурацию)**, максимальное количество игроков и другие параметры.

## Использование

1. Запустите сервер Minecraft с установленным плагином Geyser.
2. Игроки, использующие устройства с Bedrock Edition, могут подключиться к серверу Minecraft, указав его IP-адрес и порт в клиенте Bedrock Edition.
3. При подключении игрокам будет предложено ввести свое имя пользователя на сервере.
4. Игроки Bedrock Edition смогут взаимодействовать с игроками Java Edition на сервере Minecraft, общаться в чате, просматривать других игроков и выполнять основные игровые действия.

## Расширенная конфигурация

1. Для расширенной настройки плагина Geyser откройте файл "config.yml".
2. Ниже приведены некоторые из ключевых параметров конфигурации:
   - `motd`: Здесь вы можете настроить сообщение дня для Bedrock Edition игроков.
   - `remote`: Установите значение "true", если хотите разрешить удаленное подключение к серверу. Установите "false", чтобы ограничить подключение только к локальной сети.
   - `ping-passthrough`: Установите значение "true", чтобы передавать запросы пинга от клиентов на сервер. Установите "false", чтобы отключить это.
   - `max-players`: Поставьте максимальное количество людей которое вы хотите чтобы было на сервере.
   - `metrics`: Установите значение "true", чтобы разрешить отправку анонимных метрик об использовании плагина разработчикам Geyser.

## Отладка и поддержка

1. В случае возникновения проблем или ошибок при использовании плагина Geyser, проверьте файлы журналов вашего сервера Minecraft для получения подробной информации об ошибке.
2. Посетите официальный репозиторий плагина [Geyser на GitHub](https://github.com/GeyserMC/Geyser) или их [Discord сервер](https://discord.com/invite/geysermc) для получения поддержки от разработчиков.
3. При сообщении об ошибке или запросе поддержки предоставьте информацию о вашей конфигурации сервера и ошибках разработчикам плагина.