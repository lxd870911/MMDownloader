# MMDownloader
마루마루 다운로더 신규 프로젝트

* 해당 프로그램은 HtmlUnit 라이브러리를 사용하였으며,  Apache License 2.0을 따르고 있습니다.
* HtmlUnit : http://htmlunit.sourceforge.net/
* 해당 프로그램 및 소스코드는 개인적인 자바 공부를 위하여 작성되었습니다.
* 저작권법을 준수하여야 합니다.
* 다운로드 받은 웹툰은 개인 소장용도로만 이용하여야 하고, 재배포, 판매 등의 행위를 하면 안됩니다.
* 해당 소스코드나 프로그램을 악용하여 발생하는 상황에 대해 어떠한 책임도 지지 않습니다.

사용 방법
* 기존 wasabisyrup 등이 들어간 아카이브 주소만 다운로드 되던 것을 "아무 주소"나 넣어도 다운로드가 가능하게 개선하였습니다.
* 다운로드 경로는 C:\Marumaru\ 입니다.

작동과정 중 유의사항
* HtmlUnit을 이용하여 자바스크립트를 포함하여 페이지를 유닛테스트 개념으로 읽어들인 뒤, 이미지를 다운로드 하는 방식이여서, 초기 자바스크립트 파싱 과정(=이미지 추출과정)에서 시간이 다소 소요될 수 있습니다.
* 다운로드 속도는 한 편당 최소 1분 ~ 최대 5분까지 소요되며, 이는 마루마루 서버 상태와 PC의 네트워크 속도에 제일 큰 영향을 받습니다.


--- ver 0.1.0 ---
* 한 편씩 다운로드 & 여러편 다운로드를 "만화 다운로드" 기능 하나로 합침 -> 프로그램이 알아서 판단하여, 한 편만 있으면 한편만 다운 or 여러편이 있으면 전체 다운로드 진행
* 여러편 다운로드에 한해서 부모폴더생성 지원 ex) C:\Marumaru\원피스\원피스 337화\
* 기존 wasabisyrup 등이 들어간 아카이브 주소만 다운로드 되던 것을 "아무 주소"나 넣어도 다운로드가 가능하게 개선

--- ver 0.0.1 ---
* 한편씩 다운로드 기능 지원
* 다운로드 폴더 열기 기능 지원
