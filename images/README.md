# images/

이 폴더에 넣은 이미지는 사이트에서 다음 URL로 접근할 수 있습니다.

```
https://sieunjae.com/images/<파일명>
```

## 파일명 규칙 (권장)

- **영문 소문자 + 숫자 + 하이픈만** 사용 (예: `bibim-1.jpg`)
- 한글 파일명도 동작하지만 URL에서 인코딩(`%EA%B2…`)되어 보기 어려움
- 공백 대신 하이픈(`-`) 사용
- 확장자는 소문자 (`.jpg`, `.png`, `.webp`)

## 추가하는 법

1. 이 폴더에 이미지 파일을 복사
2. 터미널에서 commit + push
   ```bash
   git add images/
   git commit -m "add image: <설명>"
   git push
   ```
3. Google 스프레드시트의 `사진_URL` 또는 `코스이미지_URL` 칸에 URL 입력
   ```
   https://sieunjae.com/images/bibim-1.jpg
   ```
4. 사이트 새로고침해서 확인

## 권장 사이즈/용량

- 가로 800~1200px 정도면 충분 (모바일 카드 기준)
- 한 장당 300KB 이하 권장 (페이지 로딩 속도)
- `tinypng.com` 같은 도구로 압축 추천
