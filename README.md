# Markdown converter for Tistory

## 설치법
1. 티스토리 관리 페이지로 이동 후 HTML/CSS 편집 메뉴로 이동하여 '파일업로드'' 탭을 선택합니다.
2. [추가] 버튼을 눌러 `tistory-markdown-min.js` 파일 업로드합니다.
3. 'HTML/CSS' 탭으로 이동하여, `</body>` 태그의 바로 윗부분에 아래의 코드를 추가합니다.
    <script src="./images/tistory-markdown-min.js"></script>
    <script>markdown();</script>

## 사용법
1. 글쓰기 화면에서 HTML모드로 전환 후 Markdown을 사용할 부분을 `<pre class="markdown">` 태그와 `</pre>` 태그로 감쌉니다.
2. [저장] 버튼을 눌러 글 작성을 완료하면 자동으로 Markdown으로 번역됩니다.
