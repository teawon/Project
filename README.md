# TTT
2020 8월 20일

독서토론 결과물들을 게시물 형태로 저장하고 편하게 볼 수 있도록 만든 게시판형 사이트.

이미지가 보이는 게시판 / 글을 올리는 게시판 / 책을 소개하거나 추천하는 card형식의 게시판
파일 업로드 및 다운로드
댓글 기능

1. 이미지 썸네일 형성 방법  - 이미지 게시판에 첫번째로 올라오는 png파일을 gif형태의 썸네일로 바꾸어 해당번호의 썸네일 번호에 해당하는 이미지를 불러옴
2. 파일 - 파일 db를 따로 만들고 게시물 ID값을 통해 게시판에서 불러올 수 있도록 설정
3. 파일의 다량 첨부 -> 파일추가 버튼을 통해 파일 업로드 창 늘림
4. 댓글의 새로고침 안됨문제  -> 해당 게시글에 해당하는 값을 받아와 해당 게시판으로 강제 이동하여 새로고침
5. 댓글을 지웠을 때 게시물의 총 댓글 수 반영안됨 오류 -> 본래 댓글ID 외에 게시물 아이디도 인자로 2개 넘겨서 위와 같은 방법으로 bbsID의 댓글 수 감소 적용 / 새로고침 해결
6. 게시물을 확인 후 목록버튼을 누를 떼 (hisroty -1) 댓글작성을 통한 새로고침이 된 상태라면 목록버튼이 제자리로 옴
-> ㅜㅜ
