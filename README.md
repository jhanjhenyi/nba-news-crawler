# NBA News Crawler

[NBA 台灣 | 聯合新聞網](]https://nba.udn.com/nba/index) 的焦點新聞爬蟲實作

![](images/nba_news.png)

## 使用到的東西

- [Python 3.7](https://www.python.org/)
- [Django](https://www.djangoproject.com/)
- [Django REST framework](https://www.django-rest-framework.org/)
- [Requests-HTML](https://html.python-requests.org/)

## 爬蟲

手動執行爬蟲程式，預計之後利用程式的排程來自動爬蟲

```
$ python crawler\nba_crawler.py
```
```
-----Crawler Start-----
3440503 安比德開季好表現 堪比張伯倫、巴克利 ok.
3440218 輸球照嗆聲佐蒙德 安比德：我在他腦裡很有份量 ok.
3441207 復出助湖人奪首勝？ 布萊恩笑答：5連敗就考慮 ok.
...
...
...
3431041 尼克小將上演精彩暴扣 喜獲傳奇灌籃王盛讚 ok.
3430335 表態積極洽談續約 格林盼生涯終老勇士 ok.
3430684 詹皇湖人首戰大秀灌籃 紫金軍團半場2分落後 ok.
Save Completed.
-----Crawler End-----
```

## 預計
- 
