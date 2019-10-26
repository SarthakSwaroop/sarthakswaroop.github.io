---
layout: "project"
type: "website"
title: "Finance"
description: "A web app that allows user to play with real time stocks."
icon: "https://raw.githubusercontent.com/SarthakSwaroop/RAW/master/icon-code-9.jpg"
repo: "SarthakSwaroop/financee"
git: "git://github.com/SarthakSwaroop/financee"
links: 
  - name: "GitHub"
    url: "https://github.com/sarthakswaroop"
    icon: "https://github.com/favicon.ico"
contributors: 
  - login: "Sarthak Swaroop Bansal"
    avatar: "https://raw.githubusercontent.com/SarthakSwaroop/RAW/master/mee.jpg"
    url: "https://github.com/sarthakswaroop"
languages: 
  - "HTML"
  - "CSS"
  - "JavaScript"
isDocs: "false"
isWiki: "false"
pushed: "2019-09-08T17:10:38Z"
---
!(https://raw.githubusercontent.com/SarthakSwaroop/RAW/master/Screen%20Shot%202019-10-27%20at%2012.20.38%20AM.png)
(https://raw.githubusercontent.com/SarthakSwaroop/RAW/master/Screen%20Shot%202019-10-27%20at%2012.21.22%20AM.png)
Finance, a web app via which you can manage portfolios of stocks. Not only will this tool allow you to check real stocks' actual prices and portfolios' values, it will also let you buy (okay, "buy") and sell (okay, "sell") stocks by querying AlphaVantage for stocks' prices.

Indeed, AlphaVantage lets you download stock quotes in CSV format via URLs like https://www.alphavantage.co/query?function=TIME_SERIES_INTRADAY&symbol=MSFT&interval=1min&apikey=demo&datatype=csv. Notice how Microsoft’s symbol (MSFT) is embedded in this URL (as the value of the HTTP parameter called symbol); that’s how AlphaVantage knows whose data to return. Notice also the value of the HTTP parameter called function. The value of that parameter tells AlphaVantage which fields of data to return to you. Incidentally, the API might sometimes returns prices in currencies other than US dollars (USD) without telling you which, but we’ll assume everything’s in US dollars for simplicity.
