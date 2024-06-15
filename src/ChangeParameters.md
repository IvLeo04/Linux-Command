# Изменение сетевых параметров
### Для начала переходим в папку `/etc/netplan` и в текстовом редакторе начинаем работу с файлом `00-installer-config.yaml`
![Alt text](../materials/%D0%A0%D0%B8%D1%81%D1%83%D0%BD%D0%BE%D0%BA11.jpg)
### Меняем `addresses`, `gateway4`, `nameservers`
![Alt text](../materials/%D0%A0%D0%B8%D1%81%D1%83%D0%BD%D0%BE%D0%BA12.png)
### После сохранения редактирования, командой `sudo netplan try` проверяем на наличие ошибок и далее смотрим, произошли ли изменения.
![Alt text](../materials/%D0%92%D1%81%D1%82%D0%B0%D0%B2%D0%BA%D0%B0.png)

![Alt text](../materials/%D0%92%D1%81%D1%82%D0%B0%D0%B2%D0%BA%D0%B02.png)
### Пропингуем удаленные хосты
![Alt text](../materials/%D0%A0%D0%B8%D1%81%D1%83%D0%BD%D0%BE%D0%BA13.png)