# Oracle Instant Client 설치하기

## 1. Download Client Package

[Oracle Instant Client Downloads](https://www.oracle.com/database/technologies/instant-client/downloads.html)

- Basic Package
- SQL*Plus Package
- Tools Package
- SDK Package
- JDBC Supplement Package
- ODBC Package



## 2. PATH 설정 (환경 설정)

### Linux / Mac OS X

#### 심볼릭 링크 생성

```bash
mkdir ~/lib
ln -s ~/instantclient_19_3/libclntsh.dylib ~/lib/
```



#### .bash_profile 수정

```bash
export PATH="~/instantclient_19_3:$PATH"
```



### Windows

#### 환경변수 설정

```
PATH 추가
C:\oracle\instantclient_19_3

TNS_ADMIN
C:\oracle\wallet
```

