# Screen-Documentation

## Logistics Info Screen 
<img width="376" alt="Screenshot 2024-08-29 at 16 05 40" src="https://github.com/user-attachments/assets/deea402a-1021-409a-ba2d-11cfd05f0446">


**Integrated Api for this Screen**
```
URL: https://www.greatmall.uz/api/logisticsOrder/number
Method: GET
```

---------- Request ----------

**Headers**
```
Api-Device-OS: Android
Api-language: zh_cn
Form-Type: app
Ptlangue: uz
X-Token: Bearer eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJ3d3cuZ3JlYXRtYWxsLnV6IiwiYXVkIjoid3d3LmdyZWF0bWFsbC51eiIsImlhdCI6MTcyNDkyNzM4NywibmJmIjoxNzI0OTI3Mzg3LCJleHAiOjE3NDA0NzkzODcsImp0aSI6WzMyNzcxOSwidXNlciJdfQ.PDKJbGYmH6SQHJqzoAuZP1-vEnGCIzzTayjGurz3tac
Accept: application/json
Accept-Charset: UTF-8
User-Agent: Ktor client
Content-Type: application/json
```

---------- Response ----------

```
{
  "status": 200,
  "message": "Muvaffaqiyat",
  "data": {
    "all": 1,
    "no_pay": 1,
    "is_pay": 0,
    "is_done": 0
  }
}
```
**Info fields**
```
'all' - all logistic orders number
'no_pay' - pending payment logistic orders number
'is_pay' - the number of logistic orders on the way
'is_done' - delivered logistic orders number
```

1. If this screen is visited Api is called.
2. If Api will be Loading _progressbar_ should be shown
3. When data will come from Api 

<img width="814" alt="Screenshot 2024-08-29 at 16 32 26" src="https://github.com/user-attachments/assets/fcc34d45-6b12-4cc4-bf63-582b48b60f33">



