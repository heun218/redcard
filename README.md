# RedCard
[클래스카드](http://classcard.net)의 암기, 리콜, 스펠 과정을 자동으로 진행해주는 프로그램입니다.

Python 3.9.4에서 제작되었으며, Selenium 패키지를 사용합니다. **pip install selenium으로 패키지 설치 후 사용 및 수정해 주세요.**

**본 프로그램을 수행평가 등 부정하게 사용하여 일어나는 모든 불이익과 실력의 하락에 대한 책임은 본인에게 있습니다.**

**chrome이 설치되어있어야 합니다.** 또한 그에 맞는 chromedriver.exe 파일 또한 있어야 하는데, [이 링크](https://chromedriver.chromium.org/downloads)에서 자신의 크롬 버전과 맞는 chromedriver를 다운로드 받아 같은 폴더에 두세요.


본 레포에는 4개의 파일이 있습니다.

 - main
 - ccard
 - extccard
 - user(.txt)
 
main에서 ccard, extccard의 코드를 불러와 실행합니다.
ccard : 단어 수의 일의자리 숫자가 1,2,3이 아닌 경우
extccard : 위와 반대의 경우
user : 클카의 유저 정보, 세트 번호를 입력하는 공간입니다. 형식은 아이디,비밀번호,클래스카드 세트의 번호입니다. 띄어쓰기와 대소문자 모두 구분합니다. 콤마도 입력해 주세요.

클카 세트 특성 상 디폴트가 10개에 한 세트이지만, 마지막 세트는 10,11,12,13개까지 한 세트로 치기 때문에 코드 상에서 오류가 발생하는 것을 막기 위해 일부러 나눠놨습니다.

물론 파일 하나로 통합할 수도 있지만 귀찮기도 하고 능력이 부족하기도 하고..

그리고 보시면 아시겠지만 코드가 좀 난잡합니다. 전공도 직업도 아직은 없다보니..
