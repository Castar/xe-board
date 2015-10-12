# 릴리즈 노트 1.4.4 #

  * 확장 변수로 검색 시 오류 문제 해결 ([issue 68](https://code.google.com/p/xe-board/issues/detail?id=68))
  * 목록에서 제목 굵게, 색상이 적용되지 않는 문제 해결 ([issue 22](https://code.google.com/p/xe-board/issues/detail?id=22))
  * xe\_guestbook 스킨에서 확장 변수 표시가 올바르지 않은 문제 해결 ([issue 4](https://code.google.com/p/xe-board/issues/detail?id=4))
  * 비추천 수를 목록 설정에 추가 ([issue 6](https://code.google.com/p/xe-board/issues/detail?id=6))
  * 방명록, 블로그 스킨에서 댓글 쓰기 창이 나오지 않는 문제 해결 ([issue 43](https://code.google.com/p/xe-board/issues/detail?id=43))
    * 기본 column list에 comment\_status 추가
  * 기본 스킨에 확장 변수로 정렬하는 기능 추가 ([issue 45](https://code.google.com/p/xe-board/issues/detail?id=45))
  * 방명록, 블로그 스킨과 같이 한 페이지에 댓글이 여러개 나오는 경우 각 댓글의 페이지를 별도로 네이게이션할 수 있도록 개선 ([issue 9](https://code.google.com/p/xe-board/issues/detail?id=9))
    * _document\_srl_`_`cpage 변수를 사용하도록 변경. 서드파티 스킨은 [r170](https://code.google.com/p/xe-board/source/detail?r=170) 을 참고하여 스킨 변경 필요.
  * 댓글이 비허용된 글의 댓댓글 링크를 나오지 않도록 변경하고 댓글 쓰기 액션으로 바로 접근 시 에러 메시지 표시하도록 개선 ([issue 58](https://code.google.com/p/xe-board/issues/detail?id=58))
  * call-time pass-by-reference 코드 제거 ([issue 80](https://code.google.com/p/xe-board/issues/detail?id=80))
  * xe\_guestbook 스킨, 스킨 타입이 blog일 경우 목록에서 document 테이블의 모든 컬럼을 가져오도록 변경 ([issue 81](https://code.google.com/p/xe-board/issues/detail?id=81))
    * 임시 방편으로 차기 버전에 좀더 나은 방법으로 개선 예정
  * 테마에 의한 일괄 스킨 적용을 피할 수 있는 스킨 고정 기능 추가 ([issue 83](https://code.google.com/p/xe-board/issues/detail?id=83))
  * 확장 변수가 작성된 언어와 다른 언어로 목록을 볼 때 확장 변수 값이 나오지 않는 문제 수정 ([issue 183](https://code.google.com/p/xe-board/issues/detail?id=183))
  * 모바일에서 alert 메시지가 나오지 않는 문제 해결 ([issue 88](https://code.google.com/p/xe-board/issues/detail?id=88))
  * UI/UX 관련 개선 ([issue 96](https://code.google.com/p/xe-board/issues/detail?id=96), [issue 91](https://code.google.com/p/xe-board/issues/detail?id=91), [issue 90](https://code.google.com/p/xe-board/issues/detail?id=90), [issue 73](https://code.google.com/p/xe-board/issues/detail?id=73), [issue 26](https://code.google.com/p/xe-board/issues/detail?id=26), [issue 76](https://code.google.com/p/xe-board/issues/detail?id=76))