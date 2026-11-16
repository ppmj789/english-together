# 영어 같이 하기

셋이서 **매일 스픽 + 한 주에 자막 없이 영상 3편** 하는 걸 체크하는 작은 앱.

- 화면: `index.html` 하나 (GitHub Pages) — https://ppmj789.github.io/english-together/
- 백엔드: 미지의 서재(read-together)와 같은 Supabase 프로젝트의 `eng_*` 테이블
- DB 마이그레이션은 **read-together 저장소** `supabase/migrations/20261116120000_eng_study.sql` 에 있음
  (같은 DB의 마이그레이션 이력을 한 저장소로 모으기 위해). 테이블을 바꿀 땐 그쪽에 새 파일 추가.

## 쓰는 법
1. Simon · MiMi · Jamie 중 내 캐릭터 고르기 (사람은 index.html 의 PEOPLE 에 고정)
2. My Todos 에서 매일 `Speak 레슨` 체크 — 셋 다 하면(또는 패스권) 달력 그날이 세 사람 색으로 칠해짐 ✨
3. 이번 주 영상 3편(index.html 의 `VIDEO_SETS`)을 보고 하나씩 체크 — 주(월~일)마다 0/3 부터 새로
4. 패스권은 한 주 1장, My Todos 오른쪽 위 `🎫 패스권 쓰기`
5. Crew 에서 오늘 리액션(👏 😂 ❤️)·아직 안 한 사람에게 💬 카톡 독촉

영상을 바꾸려면 `VIDEO_SETS` 에 `{from:'그 주 월요일', list:[...]}` 묶음을 추가.
