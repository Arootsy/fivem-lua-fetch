
HOW TO USE:

```
local fetch = require '@fivem-lua-fetch.server.fetch'
```



EXAMPLE: 

```
local response = fetch("http://127.0.0.1", {
    method = "GET",
    headers = {
        ["x-api-key"] = "NICEKEY",
        ["Content-Type"] = "application/json"
    },
    data = json.encode({
        name = "Arootsy"
    })
})
```