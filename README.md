![alt tag](https://cloud.githubusercontent.com/assets/3773993/17329791/cd5afef8-58cc-11e6-9a63-0a7b0c61b407.png)


https://github.com/pranavraja/youtube
http://www.last.fm/api

https://github.com/fent/node-youtube-dl

last.fm
Application name	Music generator
API key	            d6de1272194e70b5f0f25834eba24155
Shared secret	    5cbe9bb0e600ce86a71c4d3b22be681b
Registered to	    mpak_


Tasks:

Эквалайзер (done)

UI плейлиста
- Листание
- Клик на трек в плейлисте
- Загрузка с youtube (done)
- Интерфейс для ожидания загрузки с youtube, прогресс

Общие контролы
- Громкость
- Прогресс трека
- Следующий трек (или дизлайк, )

Теги
- Показывать выбранные теги сверху и снизу

Интеграция с другими сервисами

Переключение на видео


Bugs:

1. Если не проставлять height: 500px; - пропадает -webkit-app-region: drag; 
2. При этом если окно меньше 500, все начинает ехать при скроле.
3. Градиент тормозит?
4. Если листать вниз клавишами, скрол проезжает и не работает (и вообще - это для громкости)
5. Плейлист не прозрачный к концу (done)
6. Плейлист должен быть в половину высоты, сейчас n итемов
7. Эквалайзер тормозит? и тоже на половину ширины нужно