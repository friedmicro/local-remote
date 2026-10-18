# local-remote
A solution for running bash scripts\system commands over the a local network over http. Please take a look at `config.json` for a configuration example.

## Run\use
To run use `node main.js` and to control use: `curl -X POST http://IP:3000/<action key>/ -H "Content-Type: application/json" -d '{"key_name": "key_value"}'`.
