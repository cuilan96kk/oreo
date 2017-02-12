# Oreo
_a responsive skin for Tistory Blog_

###설치방법
* github에서 다운로드
* 티스토리 블로그 관리창에서 적용시키기
 1. 다음 경로로 이동: 꾸미기 -- 스킨 -- 스킨등록
 2. oreo/oreo 폴더에 있는 내용물을 모두 업로드 및 저장 후 적용

###사용한 패키지
1. [Jquery](https://jquery.com)
2. [Bootstrap](http://getbootstrap.com)

###Release Log
####ver 0.2
* Font Awesome 제거, 대신 Bootstrap glyphicon으로 대체
* 유지 보수 가능한 선에서 최소화(minify)
* 폴더 구조 변경
 1. images 폴더 제거: 어짜피 티스토리에서 업로드할 때 자동으로 images 폴더가 만들어지므로
 2. verbose 폴더 추가: 직접 편집하기 쉽도록 최소화되지 않은 파일을 추가
* 버튼 그룹 디자인 반영

####ver 0.1
Bootstrap 커스텀 스타일 사용
* 상단 헤더
 1. 좌측 블로거 썸네일, 우측 메뉴(공지, 태그, 방명록, 검색, RSS)
 2. 그 밑에 카테고리 메뉴: 상위 메뉴만 보임
 3. 붙박이 공지사항 리스트
* 중단 메인
 1. 포스트 제목, 카테고리, 날짜, 썸네일
 2. 방명록에서 사용자들의 썸네일은 구현하지 못함
 3. 위치로그는 구현되지 않음
 4. 페이징
* 하단 사이드바: 최근 글/댓글, 태그, 글 저장소, 조회수만 구현

