
# KTStartPage

Стартовая страница KlodskaTeam для браузеров. Она имеет систему поиска от гугла и панель ссылок снизу.
[Попробуйте демку!](http://spage.klodskateam.rf.gd/)


## Установка

Скачайте репозиторий и загрузите на хостинг с поддержкой **JavaScript**
### Смена поисковой системы

Перейдите в index.html и на 122 строчке кода поменяйте поисковую систему на свою.
Чтобы узнать, что нужно вставлять, перейдите на поисковик, который хотите поставить, поищите ``test``, скопируйте адрес так, чтобы вашего запроса не было:
``https://www.google.com/search?q=test&oq=test&gs_lcrp=EgZjaHJvbWUqDwgAEEUYOxiDARixAxiABDIPCAAQRRg7GIMBGLEDGIAEMg0IARAAGIMBGLEDGIAEMgoIAhAAGLEDGIAEMg0IAxAAGIMBGLEDGIAEMgcIBBAAGIAEMgcIBRAAGIAEMgcIBhAAGIAEMgcIBxAAGIAEMgYICBBFGEHSAQgxMzY0ajBqMagCALACAA&sourceid=chrome&ie=UTF-8`` в ``https://www.google.com/search?q=``. Вставьте результат в код и всё.
### Смена ссылок снизу

Перейдите в index.html и на 109 строке добавьте вашу ссылку.

### Смена фона

Тут ваще легко, на 15 строке кода 
```css
background-image: url('res/bg/bg.svg');
```
меняем ``res/bg/bg.svg`` на любую картинку
