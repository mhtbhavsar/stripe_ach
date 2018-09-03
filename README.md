### plaid-stripe ACH payment gateway example

[Quickstart guide](https://plaid.com/docs/quickstart)

``` bash
reference from : git clone https://github.com/plaid/quickstart.git

npm install

# The above call defaults to test/tartan credentials.

# Substitute other values with any of the following:
APP_PORT=8000 \
PLAID_CLIENT_ID=[CLIENT_ID] \
PLAID_SECRET=[SECRET] \
PLAID_PUBLIC_KEY=[PUBLIC_KEY] \
PLAID_ENV=sandbox \
node index.js

# Go to http://localhost:8000
```
