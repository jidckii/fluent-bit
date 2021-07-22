# fluent-bit docker labels

[EN](https://github.com/jidckii/fluent-bit/blob/master/README.md)

Данная сборка рассчитана на сбор логов из docker / docker swarm.  
Включает скрипт на lua(спасибо [@gitfool](https://github.com/gitfool) [источник](https://github.com/fluent/fluent-bit/issues/1499)), который создаёт fields из лейблов контейнеров.  
Также фильтр для multiline сообщений.  
