## 이더 조회 예제

```
npm install -g bower
bower install
```

index.html 확인

아래 주소에서 키를 발급 받은뒤에 index.html에 하단소스에 적용해주세요

https://infura.io/

```
web3.setProvider(new web3.providers.HttpProvider("https://ropsten.infura.io/v3/키를발급받으세요"));
```