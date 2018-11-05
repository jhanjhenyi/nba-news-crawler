# NBA News Crawler

[NBA 台灣 | 聯合新聞網](https://nba.udn.com/nba/index) 的焦點新聞爬蟲實作

![](images/nba_news.png)

前端嘗試不使用 jQuery，僅用 Bootstrap CSS 跟 Font Awesome 的 icons 來實作，但前端不是我的重點，有時間再來重構（？

## 功能簡介

- 首頁預設載入第一組資訊，按新聞發佈時間先後排序
- 滑到底按下 More 會載入下一組新聞資料
- 按下新聞中的 Read More 會跳出 Modal 顯示新聞內容

## 使用到的東西

- [Python 3.7](https://www.python.org/)
- [Django](https://www.djangoproject.com/)
- [Django REST framework](https://www.django-rest-framework.org/)
- [Requests-HTML](https://html.python-requests.org/)
- [schedule](https://github.com/dbader/schedule)
- [Bootstrap](https://getbootstrap.com/)
- [Font Awesome](https://fontawesome.com/)
- [Heroku](https://www.heroku.com/)

## 爬蟲

因為是練習用，因此爬蟲預設只爬十頁

爬蟲程式是透過 [schedule](https://github.com/dbader/schedule) 來進行排程，之後再試看看 Celery 或 Django Q
