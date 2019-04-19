# buy_module
A transactional handling for the purchase of desired stocks. 

# Getting service started
From within the root directory: npm install npm run react-dev npm run db:setup npm start

Related projects
https://github.com/menintights/buyComponent

# API routes
| Route                                              | Result                              |
|----------------------------------------------------|-------------------------------------|
| `GET/stocks/:ticker`                               | Initial Page Load                   |
| `GET/api/stocks/:ticker`                           | Display Company API Data            |
| `GET/api/accounts/:account_number`                 | Display Account API Data            |
| `Update/accounts/:account_number`                  | Purchase stock                      |
| `Create/Update/Delete/stocks/:ticker/dev`          | Admin changes to listed companies   |
| `Create/Update/Delete/accounts/:account_number/dev`| Admin changes to user account       |
