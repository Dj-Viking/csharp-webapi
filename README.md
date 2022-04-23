# Run server

```sh
sh server.sh
```

# Test Endpoint
- NOTE: will have to authorize the keychain for the development certificate
- and by default will redirect to the https route because of
```cs  
app.UseHttpsRedirection();
```
- GET /weatherforecast
  * https://localhost:7069/weatherforecast
  * Or http://locahost:5198/weatherforecast
