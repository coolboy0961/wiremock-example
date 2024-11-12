## 一般実行
```
java -jar wiremock-standalone-3.9.2.jar --port 8090
```

## レコーディング実行
```
java -jar wiremock-standalone-3.9.2.jar --port 8090 --proxy-all="https://dummyjson.com" --record-mappings
```