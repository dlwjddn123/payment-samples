# payment-virtualaccount-api/node

Node.js 를 이용한 결제창 샘플입니다. Express로 구성되었습니다.

## 실행 요구조건

- Node.js >= 14.0.0
- npm

## 테스트하기

샘플소스를 copy하신후

```sh
$ npm install
$ node app.js
```

서버가 실행 된 후, `http://localhost:8080/virtual_account/`으로 접속해서 테스트할 수 있습니다.

* 돌아온 결과 값에서 `virtualAccount.accountNumber`, `virtualAccount.bank`으로 입금해야 할 가상계좌 정보를 결제 고객에게 알려주세요.