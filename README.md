# TradingviewWebhook

Webhook URL (POST ONLY): https://webhooknextjs.vercel.app/api/webhook

Postman Testing
Tradier
{
  "Broker": "Tradier",
  "Action": "buy",
  "Ticker": "NVDA",
  "Quantity": "10",
  "LimitPrice": "840",
  "Tradier_Account_ID": "VA712334962",
  "TradierAccessToken": "GQkjksJLASKuefDfhUiOISBSWKwT"
}

Alpaca
{
  "Broker": "Alpaca",
  "Action": "buy",
  "Ticker": "NVDA",
  "Quantity": "10",
  "LimitPrice": "840",
  "API_KEY": "PfgfgBHJAJSkjOTRDaOS",
  "API_SECRET": "IZtC2dffdfHwjfgfgfxidd"
}


JSON for Tradingview Alert

Tradier
{
  "Broker": "Tradier",
  "Action": "buy",
  "Ticker": "{{ticker}}",
  "Quantity": "10",
  "LimitPrice": "{{close}}",
  "Tradier_Account_ID": "VA712323962",
  "TradierAccessToken": "GQkjksJkHsdffDfhUiOISBSWKwT"
}

Alpaca
{
  "Broker": "Alpaca",
  "Action": "buy",
  "Ticker": "{{ticker}}",
  "Quantity": "10",
  "LimitPrice": "{{close}}",
  "API_KEY": "PfgfgBHJAJ2sdSkjOTRDaOS",
  "API_SECRET": "IZtC2sdsdasaUIdffdfHwjfgfgfxidd"
}

Enable After-hour Trading
Tradier
{
  "Broker": "Tradier",
  "Action": "buy",
  "Ticker": "{{ticker}}",
  "Quantity": "10",
  "LimitPrice": "{{close}}",
  "Tradier_Account_ID": "VA712323962",
  "TradierAccessToken": "GQkjksJkHsdffDfhUiOISBSWKwT",
  "Testing": "true"
}

Alpaca
{
  "Broker": "Alpaca",
  "Action": "buy",
  "Ticker": "{{ticker}}",
  "Quantity": "10",
  "LimitPrice": "{{close}}",
  "API_KEY": "PfgfgBHJAJ2sdSkjOTRDaOS",
  "API_SECRET": "IZtC2sdsdasaUIdffdfHwjfgfgfxidd",
  "Testing": "true"
}

Change Action to sell for sell signal, for example
{
  "Broker": "Tradier",
  "Action": "sell",
  "Ticker": "{{ticker}}",
  "Quantity": "10",
  "LimitPrice": "{{close}}",
  "Tradier_Account_ID": "VA712323962",
  "TradierAccessToken": "GQkjksJkHsdffDfhUiOISBSWKwT",
  "Testing": "true"
}
