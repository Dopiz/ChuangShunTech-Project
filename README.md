# nice to meet you
- \[x] 抓取 https://nba.udn.com/nba/index?gr=www 中的焦點新聞。
- \[x] 使用 [Django](https://www.djangoproject.com/) 設計恰當的 Model，并將所抓取新聞存儲至 DB。
- \[x] 使用 [Django REST Framework](http://www.django-rest-framework.org/) 配合 AJAX 實現以下頁面：
	 * 焦點新聞列表
	 * 新聞詳情頁面
- \[ ] 以 Pull-Request 的方式將代碼提交。
	
## 進階要求
- \[x] 實現爬蟲自動定時抓取。
	`利用 django-q 在 Scheduled tasks 裡增加任務排程。`
- \[ ] 每當抓取到新的新聞時立即通知頁面。
	`try django websocket`
- \[ ] 將本 demo 部署至服務器並可正確運行。


## Requirements
```
django
selenium
beautifulsoup4
django-q
requests
djangorestframework
markdown
django-filter
```