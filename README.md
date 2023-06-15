# set_defaultbrowser
Установка браузера по умолчанию в macOS
==============

Утилита командной строки для установки браузера по умолчанию в macOS.
Требует подтврждения пользователя.

Установка
-------

```
make
```

Использование
-----

```
defaultbrowser {browser_name}
```

Например

```
defaultbrowser chrome
```

Запущенный без аргументов показывает список доступных handler'ов HTTP/HTTPS. Текущий отмечен звездочкой

Как работает?
-----------------

Работает через [macOS Launch Services API](https://developer.apple.com/documentation/coreservices/launch_services).


License
-------

MIT
