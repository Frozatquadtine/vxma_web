# Bottrade
web app bot-trading version beta
docker deployments

### default 
User = 'vxma'
password = 'vxmaBot'


![image](https://user-images.githubusercontent.com/8637706/189531967-c03dec80-60aa-4b5a-9c95-7b26581710aa.png)

## Directions 
**init** -concept <br/>
├─ it must easy to use(user friendly) <br/>
├─ it must customizable <br/>
├─ it must safe an secure <br/>
├─ it must profitable <br/>
├─ it must Free <br/>

**init** -what we have now? <br/>
├─ a trend following custom strategy vxma <br/>
├─ web-ui setting(it work but noob) :D <br/>
├─ notification to Line  <br/>
├─ position sizing <br/>
├─ tailing-stop <br/>
├─ daily trend analysis <br/>
├─ any-timeframe trading <br/>
├─ callbackRate calculation for tailing-stop <br/>
├─ global limit position size <br/>
├─ minimum balance to execute open position <br/>

## Changelog
> let's begin our journey to financial freedom!
```
├─ 0.1.0 start! 
├─ 0.1.1  
│   ├── Update terminal UI
│   ├── Woring on Docker
│   ├── Better error handler
│   ├── Blazing fast 
├─ 0.1.2  
│   ├── Update Performance
│   ├── Update CCXT symbols
│   ├── Fixed bug
│   ├── New callbackRate 
├─ 0.1.3  
│   ├── Update Performance
│   ├── Update Candle faster
│   ├── Fixed bug order
│   ├── SL notification 
├─ 0.1.4  
│   ├── Added Hedging Strategy
│   ├── Update Balance faster
│   ├── Fixed bug 
│   ├── Add OrderClientId for future-use 
├─ 0.1.5
│   ├── Update CCXT to singleton instance
│   ├── Fixed min amount for notional 5.0 to 6.0 ($)
│   ├── removed daily scan sideway report
├─ 0.1.6  
│   ├── Added DefaultRiskTable for Non Setting symbols
│   ├── scan all symbols on the markets
│   ├── added MM permision to avoid max_margins
│   ├── changed way to calculate all-margin (margin * leverage)
```

[![Tradingview_VXMA](https://user-images.githubusercontent.com/8637706/196947394-d71c8ef6-9ab7-451a-b6bc-55a642c9e845.png)](https://www.tradingview.com/script/m54nptt2-VXMA-Bot)

### Need to help?
1. read TODO files for our current workflow 
2. any improvement or pointing some issues are welcome! 😁
3. I need your help 🙏

### Structure
```
vxma_web/
├── app.py
├── bot_config.csv
├── Dockerfile
├── install.sh
├── LICENSE
├── pip_freeze.txt
├── README.md
├── requirements.txt
├── run_docker.sh
├── run.sh
├── tester.py
├── TODO
├── trades.csv
├── vxma_d/
│   ├── AppData/
│   │   ├── Appdata.py
│   │   ├── Bot.py
│   │   ├── __init__.py
│   │   └── ResetDatabase.py
│   ├── Backtesting/
│   │   ├── Candle_ohlc.py
│   │   ├── __init__.py
│   ├── __init__.py
│   ├── MarketEX/
│   │   ├── CCXT_Binance.py
│   │   ├── __init__.py
│   ├── Strategy/
│   │   ├── Benchmarking.py
│   │   ├── ematalib.py
│   │   ├── __init__.py
│   │   └── vxma_talib.py
│   └── web/
│       ├── __init__.py
│       └── web.py
└── web_app.py
```
