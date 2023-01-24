# 텐져스 개발 규칙
**텐져스는 애자일 개발 방법론중 스크럼 스프린트 방식으로 개발합니다.**

</br>


> [애자일 소프트웨어 개발 선언](http://agilemanifesto.org/iso/ko/manifesto.html)

우리는 소프트웨어를 개발하고, 또 다른 사람의 개발을</br>
도와주면서 소프트웨어 개발의 더 나은 방법들을 찾아가고</br>
있다. 이 작업을 통해 우리는 다음을 가치 있게 여기게 되었다:</br>
</br>
공정과 도구보다 **개인과 상호작용**을</br>
포괄적인 문서보다 **작동하는 소프트웨어**를</br>
계약 협상보다 **고객과의 협력**을</br>
계획을 따르기보다 **변화에 대응하기**를</br>
</br>
가치 있게 여긴다. 이 말은, 왼쪽에 있는 것들도 가치가 있지만,</br>
우리는 오른쪽에 있는 것들에 더 높은 가치를 둔다는 것이다.</br>


## 개발 규칙

## [커밋 메세지](https://udacity.github.io/git-styleguide/)

> 작성 예 (*이 들어간건 필수 입력 해주세요.)

```
[issues번호*] type*: Subject*

body

footer
```

</br>

>type
```
feat: 새로운 기능 추가 (A new feature)

fix: 버그 수정 (A bug fix)

docs: 문서 수정 (Changes to documentation)

style: 코드 포맷팅, 세미콜론의 누락, 코드의 변경이 없는 경우 (Formatting, missing semi colons, etc; no code change)

refactor: 코드 리팩토링 (Refactoring production code)

test: 테스트 코드 추가, 리팩토링 코드 테스트 (Adding tests, refactoring test; no production code change)

chore: 빌드 업무 수정, 패키지 매니저 수정 (Updating build tasks, package manager configs, etc; no production code change)
```

</br>

> Example Commit Message
```
[#1] feat: Summarize changes in around 50 characters or less

More detailed explanatory text, if necessary. Wrap it to about 72
characters or so. In some contexts, the first line is treated as the
subject of the commit and the rest of the text as the body. The
blank line separating the summary from the body is critical (unless
you omit the body entirely); various tools like `log`, `shortlog`
and `rebase` can get confused if you run the two together.

Explain the problem that this commit is solving. Focus on why you
are making this change as opposed to how (the code explains that).
Are there side effects or other unintuitive consequences of this
change? Here's the place to explain them.

Further paragraphs come after blank lines.

 - Bullet points are okay, too

 - Typically a hyphen or asterisk is used for the bullet, preceded
   by a single space, with blank lines in between, but conventions
   vary here

If you use an issue tracker, put references to them at the bottom,
like this:

Resolves: #123
See also: #456, #789
```

</br>

## [gitflow](https://nvie.com/posts/a-successful-git-branching-model/)
|브랜치|용도|
|--|--|
|master|제품 출시/배포|
|develop|다음 출시/배포를 위한 개발 진행|
|release|출시/배포 전 테스트 진행(QA)|
|feature|기능 개발|
|hotfix|긴급한 버그 수정|

## Labels
|이름|설명|
|--|--|
|🐞 Bug|버그|
|🎁 Delivery|배포|
|📃 Docs|문서 작성 및 수정|
|✨ Feature|기능 개발|
|🔨 Refactor|리팩토링|
|🛠 Settings|개발 환경 설정|
|🧑‍🎨 Style|스타일링|
|✅ Test|테스트|

## 버전관리
> 버전관리는 서비스 이후 진행합니다.

## 코딩 컨벤션
- `Javascript` 또는 `Typescript`는 `ESLint`와 `Preitter`를 사용합니다. [참고 문서](https://veggie-garden.tistory.com/13)
- `Java`는 `NAVER CAMPUS HACKDAY의 Java Code Conventions`을 사용합니다. [참고문서](https://naver.github.io/hackday-conventions-java/)
