# 💱 Free and Open Source Cuban Exchange Rate API

This API just facilitates the consumption of exchange rate information, the values shown here come from third-party sources. Data is updated every 24 hours. We are not responsible for the stability of this API, please use it for your project at your own risk or host your own instance.

## 📊 Data Sources

- https://www.directoriocubano.info/cadeca/ (the same as cadeca.cu)
- https://divisascu.app/


## 🧞 API Endpoints

|Method | URL                      | Response                                         |
|:-------| :------------------------ | :----------------------------------------------- |
|GET| [/api/formal/cup](/api/formal/cup)         | Returns formal CUP exchange rate of the day      |
|GET  | [/api/informal/cup](/api/informal/cup)       | Returns informal CUP exchange rate of the day    |

## 👨‍💻 Source Code 

https://github.com/decubba/exchange-rate
