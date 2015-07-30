pyantigateX
========

Модуль для использования Antigate (antigate.com) и RuCaptcha
Пример в файле example.py

Для использования RuCaptcha перед использованией введите setRucaptcha(). Пример:

	...
	a = pyantigate.Antigate(antigate_key)
	a.setRucaptcha()

Установка
------------
    $ easy_install pyantigateX

Для работы необходим модуль [Requests](https://github.com/kennethreitz/requests)

    $ easy_install requests
