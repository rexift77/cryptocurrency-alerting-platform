**This bot supports following commands**

**/price** or **/p**  
Get the price for desired coin. The coin defaults to BTC and the base currency defaults to USD if not provided.  

Example:  
`/price BTC`  
`/price BTC USD`  
`/price XMR BTC`  
    
**/chart** or **/ch**  
Get chart for a coin at a timeframe. valid time frame values are: 1m (1 min), 3m, 5m, 15m, 30m, 1h (1 hour), 2h, 4h, 6h, 8h, 12h, 1d (1 day), 3d, 1w (1 week), 1M (1 month). The base currency defaults to USD and the time frame defaults to 1h if not provided.  

Example:  
`/chart` (defaults to BTC USD 1h)  
`/chart BTC`  
`/chart BTC USD`  
`/chart XMR BTC`  
`/chart BTC USD 1w`  
`/chart BTC USD 1M`

**/top**  
See the current prices of the top coins and market cap.

**/lower**  
Get notified when price of desired symbol goes LOWER than specified number. The base currency defaults to USD if not provided.  

Example:
`/lower ETH 25` (notify me when ETH price goes lower than 25 USD)  
`/lower BTC 1300 USD`  
`/lower XMR 0.01 BTC` (notify me when XMR price goes lower than 0.01 BTC)  
`/lower Nano 100 SAT` (notify me when Nano price goes lower than 100 Sats)  

**/higher**  
Get notified when price of desired symbol goes HIGHER than specified number.

Example:s
`/higher ETH 25` (notify me when ETH price goes higher than 25 USD)  
`/higher BTC 1300 USD`  
`/higher XMR 0.01 BTC` (notify me when XMR price goes higher than 0.01 BTC)  
`/higher Nano 100 SAT` (notify me when Nano price goes higher than 100 Sats)  

**/alerts**  
Get the current alerts.

**/clear**  
Clear current alerts.

**/yesterday**
Price yesterday for a coin

**/history**
Historical price of a coin in the past. Supports days, weeks, months, years.

Example:
`/history BTC 5 days` ( BTC price 5 days ago)
`/history BTC 3 days` (what was the price of Bitcoin 3 days ago in USD)  
`/history BTC 2 weeks`  
`/history BTC 2 months`  

**/yesterday**
Check yesterday's price

Example:
`/yesterday eth` (price of ether yesterday)

**/dropby**
Check if a coin has dropped by a percentage

`/dropby BTC 50% 1 month` (Has BTC dropped by 50% in the last 1 month)


**/watch**
Command structured 

Example:
`/watch btc drop 50% 14 days` (Percentage drop)  
`/watch btc rise 50% 1 month`  
`/watch btc drop 5000 2 days` (absolute value drop)  
`/watch btc drop 5000 from ath`  
`/watch btc drop 75% from ath`  
  
Comparisons are vs current price unless "from ath" is set   

**/ath**
What is the ATH of a coin (only checks back to Oct 2021)

`/ath BTC`


**/help**  
See this message.


Commands

`price - get the price for desired coin
p - same as /price
chart - chart for a coin at timeframe (5m, 15m, 1h, 4h, 1d, 1w, etc)
ch - same as /chart
top - See the current prices of the top coins + market cap
lower - get notified when price goes LOWER than specified number
higher - get notified when price goes HIGHER than specified number
alerts - get current alert
clear - clear current alert
help - get help about commands`


for further help or discussion please use the telegram group https://t.me/alertbotgang

Contributors
 - https://github.com/raymondclowe
