# OracleCloud_ToyProject
오라클 클라우드 + MySQL + React.js를 활용해서 Web Page 만들기
최종 기한 : 22-09-30 ( 이후 연장 가능성 있음 )


순서
### **0. 오라클 클라우드 등록**

```
https://www.oracle.com/kr/cloud/free/
```
### **1. 인스턴스 등록 및 SSH 접속 관리**
```
https://www.wsgvet.com/cloud/5
``` 

### **2. 클라우드 서버에 MySQL, React 설치**
2-1. MySQL 설치
```
```

2-2. React 설치
```
https://i5i5.tistory.com/285
```
2-3. 포트개방 (3000으로 진행)
```
https://pythonblog.co.kr/blog/30/

오라클 클라우드 재부팅시, 다시 설정해줘야함 자동설정은 추후에 업그레이드 
```
### **3. hello World Page 띄우기**
```
http://193.123.233.20:3000/
```
3-1. 리눅스 백그라운드 리액트 실행

[링크!](https://jmholly.tistory.com/entry/React-pm2-%EB%A1%9C-react-%EC%84%9C%EB%B2%84-%EC%A4%91%EB%8B%A8%ED%95%98%EC%A7%80-%EC%95%8A%EA%B3%A0-%EC%8B%A4%ED%96%89%ED%95%98%EA%B8%B0-port-%EB%B2%88%ED%98%B8-%EB%B0%94%EA%BF%94%EC%84%9C-%EC%8B%A4%ED%96%89)
```
nohup 잘못썼다가 서버 터짐. forever사용하려했는데 유지보수 끝나서 PM2사용
```

4. 화면 설계

5. 동작 설계

6. 테스트

7. 도메인 등록
```
https://blog.lael.be/post/6070
무료 도메인 및 유료도메인을 등록할 수 있다.
유료는 소유권 주장이 가능한데, 무료는 불가능한 경우가 많다. 실험삼아 무료로 해보는 것도 좋을듯
```

8. 보안

-------------------------------------------------------
# FAQ

```
1. putty를 제외한 vscode 혹은 터미널에서 ssh키를 사용하려면,
1-2에서 키를 생성하고, save가 아닌 export로 키를 저장하면 됨. 
```
```
2. 컴파일링이 너무 오래걸리니, 개발은 로컬에서 수행하고 이후에 서버에 올리는게 좋아보임
```