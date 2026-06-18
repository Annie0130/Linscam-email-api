# 林相攝影 Email API

部署到 Vercel 後，合約送出時自動寄信。

## API 端點

POST /api/send-email

## Request Body

```json
{
  "to": "customer@example.com",
  "subject": "【林相攝影】器材收購交易確認通知",
  "html": "<html>...</html>"
}
```
