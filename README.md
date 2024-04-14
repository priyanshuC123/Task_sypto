# Task_sypto


This contains completion of -

1. Fetch current holdings
2. Place buy order
3. Place sell order
4. get prices from websocket.

Using Upstox as the borker

## Functionality Details

### 1. Fetch Current Holdings
This feature allows users to view the stocks currently held in their portfolio. It retrieves information such as the stock symbol, quantity held, and current market value.

### 2. Place Buy Order
Users can use this feature to buy stocks. They specify the stock symbol, quantity, and other relevant parameters, and the application executes the buy order through the Upstox API.

### 3. Place Sell Order
Similar to placing buy orders, this feature enables users to sell stocks from their portfolio. They provide details such as the stock symbol, quantity to sell, and other necessary information, and the application executes the sell order through the Upstox API.

### 4. Get Prices from Websocket
To provide real-time data to users, the application uses Websocket to fetch live prices of stocks. This ensures that users have access to up-to-date market information.


## Implementation
The application is implemented using Python with direct API calls to Upstox for executing orders and obtaining portfolio holdings. Real-time price updates are obtained using Websocket connections to Upstox servers.

