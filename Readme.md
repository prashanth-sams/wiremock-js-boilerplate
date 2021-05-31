# WireMock JS Boilerplate
> JS project with express as backend

Install and launch wiremock server, frontend & express servers
```
npm run serve
```

```
http://localhost:8080/
  |
  |
  |---[/api/*]-> http://localhost:8081/
  |
   \
    \-[*]------> http://localhost:8082/
```

For help
```
npx wiremock --help
```


