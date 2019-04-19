buy_module
Allows the user to interactively buy and sell shares from various financial stocks.  

Getting service started
From within the root directory: npm install npm run react-dev npm run db:setup npm start

Related projects
https://github.com/menintights/buyComponent

API routes
Type	Endpoint	Operation
/stocks/:ticker	Get	Initial Page Load
/api/stocks/:ticker	Get	Display Company API Data
/api/accounts/:account_number	Get	Display Account API Data
/accounts/:account_number	Update	Purchase/Sell stock
/stocks/:ticker/dev	Create/Update/Delete	Admin changes to listed companies
/accounts/:account_number/dev	Create/Update/Delete	Admin changes to user account
