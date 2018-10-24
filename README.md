# Shiken
Shiken project using node js (training)

# Memo (How to create new node js project use Express)
1. express shiken --view=pug
2. cd shiken
3. npm install
4. npm install --save-dev nodemon
5. Add nodemon to avoid stop and restart many time
"scripts": {
    "start": "node ./bin/www",
    "devstart": "nodemon ./bin/www"
}
6. DEBUG=shiken:* npm run devstart
