# 시각화 + 인터렉션

`/git open source control view` 로 git 컨트롤 바 활성화
`<ifream>`  으로 코드 임베드

제작 목적 , 공부 자료의 모듈화 , 생산성 향상, 찾기 쉽게 하기 위함
그걸 위해서 일단은 트리구조에 친화적이게 구축하는 것을 목표로 한다

보다 나은 데이터 구조화 방식을 만들었을 때 이식하기 편하도록 직관적이게 구성하는 방향성으로

## 그런 작업을 위해 MD와 기타등등을 분리함

`ctrl+p` 하고 `>` 로 들어가지는 명령창에 `setting` 을 입력하거나
.vscode 에 seetings.json에 아래 내용이 저장하거나
```JSON
{
  "files.exclude": {
    "*.md": true
  }
}
```

설정창에 `files.exclude` 를 검색하고 설정을 바꾸거나




## 공부에 도움되는 사이트

https://ko.javascript.info/
https://webcode.tools/
https://www.gymcoding.co/acf439e5e4b04e079104439153a7f223
https://runebook.dev/ko/docs/svg/-index-
https://inpa.tistory.com/
### 추구하는 형태가 mdn 홈페이지와 유사하다
https://developer.mozilla.org/en-US/
정확히는 PWA화 한다음 성능과 기능을 강화시키고
인터넷을 거치지 않으니 리소스 소비도 줄이는 형태로 기획 중
https://github.com/mdn/
https://github.com/mdn/content

## 코드 예제 임베드 방식
```
<iframe class="sample-code-frame" title="제목" id="frame_active" width="100%" height="400" src="링크" loading="lazy"></iframe>
```

```
문서로의 링크 방식 X MD 방식으로만 사용할 수 있음 (html에서 쓰는 방식은 허용되지 않음)
안되는 예시
<a href="#frame_active"></a>
```


# 단축키
## Ctrl

|  단축키   | 기능                                       | 평점 |
|:---------:| ------------------------------------------ | ---- |
|     Q     | 현재 노트의 옵시디언 파일 탐색기 위치 열기 |      |
|     W     | 현재 파일을 파일 탐색기로 열기             |      |
|     E     | 템플릿 삽입                                |      |
|     O     | 파일 이름으로 검색 & 생성                  |      |
|     P     | 명령어 창 열기                             |      |
|     S     | 현재 문서 저장 ( 자동이 아닌가? )          |      |
|     ,     | 설정 열기                                  |      |
|     R     | 문서 이름으로 폴더 생성 후 문서 넣음       |      |
|     F     | 문장 찾기                                  |      |
|     H     | 문장 바꾸기                                |      |
| 폴더 클릭 | 같은 이름 노트 생성                        |      |
| 링크 호버 | 미리보기                                   |      |

## Alt
| 단축키 | 기능                                                | 평점 |
|:------:| --------------------------------------------------- | ---- |
|   A    | 왼쪽 사이드바 열기/접기                             |      |
|   D    | 오른쪽 사이드바 열기/접기                           |      |
|   C    | 캘린더 열기                                         |      |
|   S    | map contents - Central note 설정 ( 오른 쪽 사이드바 | 5    |
|   T    | Tag Tree 보기 ( 왼쪽 사이드바                       |      |
|   H    | 홈페이지 열기                                       |      |
|   1    | 접기 토글 모두 접기                                 |      |
|   2    | 접기 토글 모두 펴기                                 |      |

## Ctrl Shift
| 단축키 | 기능                   | 평점 |
|:------:| ---------------------- | ---- |
|   F    | 파일 검색              |      |
|   S    | map content panel 열기 |      |
|   i    | 개발자 창 열기         |      |
|        |                        |      |
