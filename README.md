# Main Application

- You need linux, unix, or mac, node.js v14 or later, pqsql prefered v12
- Clone this `Metaserverless/AppMain` repository
- Clone `Metaserverless/App1` and `Metaserverless/App2`
- Update `.applications`, put there absolute paths to `App1` and `App2`
- Run `npm ci --prod=only` just in `AppMain`
- Run `AppMain/db/setup.sh`
- Run `node server.js` from `AppMain`
- Open http://127.0.0.1:8001 or http://127.0.0.1:8002 in browser
- Stop with Ctrl+C
