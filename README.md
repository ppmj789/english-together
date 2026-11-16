# 영어 같이 하기

셋이서 매일 **스픽 + 자막 없이 영상 하나** 하는 걸 체크하는 작은 앱.

- 화면: `index.html` 하나 (GitHub Pages) — https://ppmj789.github.io/english-together/
- 백엔드: 미지의 서재(read-together)와 같은 Supabase 프로젝트의 `eng_*` 테이블
- DB 마이그레이션은 **read-together 저장소** `supabase/migrations/20261116120000_eng_study.sql` 에 있음
  (같은 DB의 마이그레이션 이력을 한 저장소로 모으기 위해). 테이블을 바꿀 땐 그쪽에 새 파일 추가.

## 쓰는 법
1. 휴대폰 뒷번호 4자리 입력 → 처음이면 이름·색 고르기
2. 오늘 칸에서 내 `스픽` `영상` 누르기
3. 셋 다 둘 다 끝내면 달력 그날이 세 사람 색으로 칠해짐 ✨
4. 오늘의 영상은 누구든 유튜브 링크를 붙여넣어 정함 (자막 꺼진 채로 재생)
