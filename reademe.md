## 一般実行
```
java -jar wiremock-jre8-standalone-2.35.1.jar --port 8090
```

## レコーディング実行
```
java -jar wiremock-jre8-standalone-2.35.1.jar --port 8090 --proxy-all="https://dummyjson.com" --record-mappings
```