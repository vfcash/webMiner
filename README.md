Live demo at [https://vfcash.uk/miner/](https://vfcash.uk/miner/)

Use emscripten to compile [https://emscripten.org/](https://emscripten.org/)

**Usage advice**; this miner can be embedded into a website, for example; hide the output <textarea> from view and use a JS script on a setInterval() loop to periodically submit the content of the miner output using AJAX to a local server side script. One can either parse the "Private Key:" outputs on the client JS side or the server side. The compiled miner script ready-to-use is located in `/bin`.
