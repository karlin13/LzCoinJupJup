# LzCoinJupJup
레진코믹스 자동 출석 프로그램

## 실행하기

### Ubuntu 16.04

```
virtualenv venv -p python3
source venv/bin/activate
pip install -r requirements.txt

npm -g install phantomjs-prebuilt

./init.sh

python main.py
```
환경변수 설명

* LZCOINJUPJUP_USERNAME, LZCOINJUPJUP_PASSWORD: 레진코믹스에 로그인 시 이용되는 이메일, 비밀번호이다

* LZCOINJUPJUP_LOGIN_METHOD: 레진코믹스는 네이버 연동 로그인, 페이스북 연동 로그인, 그 외의 이메일들로 하는 일반로그인이 있는데, 로그인의 종류를 의미한다.

* LZCOINJUPJUP_FB_USERNAME, LZCOINJUPJUP_FB_PASSWORD: 페이스북으로 레진코믹스를 공유하기 위해 사용자 인증을 할 때 쓰는 이메일, 비밀번호이다.

* LZCOINJUPJUP_TT_USERNAME, LZCOINJUPJUP_TT_PASSWORD: 트위터로 레진코믹스를 공유하기 위해 사용자 인증을 할 때 쓰는 이메일, 비밀번호이다.
