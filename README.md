Небольшая обвязка для удобной установки и запуска игр с помощью PortProton

При запуске ищет файл `$HOME/.local/share/applications/PortProton.desktop`, который создается при его установке, для определения его местоположения

Игры обязательно нужно устанавливать в `C:\Games` (регистр важен)

* **Install new game** - проверяет папку Games в префиксе INSTALL (`PortProton/data/prefixes/INSTALL/drive_c/Games`) на наличие новых игр. Если ничего не находит, предлагает запустить установщик игры. По окончании установки игра перемещается в `PortProton/games`
* **Add game entry** - позволяет добавить новую запись из уже установленных игр
* **Drop install prefix** - полностью удаляет префикс INSTALL

![image](screenshot.png)
