# movenine.github.io

`https://movenine.github.io/` 호스트 루트용 저장소입니다. 실제 사이트는 [movenine/cryptoprime](https://github.com/movenine/cryptoprime) → `https://movenine.github.io/cryptoprime/` 입니다.

검색엔진이 호스트 루트에서만 읽는 파일을 둡니다.

| 파일 | 용도 |
|---|---|
| `robots.txt` | 크롤링 허용 + 사이트맵 위치(`/cryptoprime/sitemap.xml`) |
| `index.html` | 루트 접속을 `/cryptoprime/`으로 이동 (canonical 포함) |
| `naver*.html` | 네이버 서치어드바이저 소유 확인 파일 |
| `.nojekyll` | Jekyll 처리 생략 |
