# dok 1.0
`dok` 란 보트가 개발한 패키지(? -> 파일) 관리툴이다<br>
`dok`는 따로 도크용 콘솔을 지원해준다<br>
# dok Terminal 기능
`dok` 콘솔에는 많은 기능을 지원해주는데<br>
지원해주는 기능 모음:<br>
`git clone`<br>
`hammer`,<br>
`dok` <br>
이렇게 있다<br>
그리고 `git` 은 git clone기능만 있다<br>
____________________________________________________________________________
# dok command
`dok` 터미널을 켜 준다 <br>
그리고 첫번째 예제인 `html`을 생성해보자<br>
dok 터미널에 이렇게 입력해준다<br>
`dok html -y`<br>
그럼 예제 파일이랑 같이 html이 만들어진다 <br>
`-y`는 yaga < 예제라는 것이다<br>
<pre><code>
[dok html -y]
|-- 현재 디렉토리
|   |-- index.html
|   |-- script.css
__________________
</code></pre>
생성된 예제 html을 마음대로 수정해도 상관이 없다.
`dok html`을 쓰면 그냥 html파일을 만들 수 있다
<pre><code>
[dok html]
|-- 현재 디렉토리
|   |-- index.html
|   |-- dok.js
__________________
</code></pre>
만약 dok_package 폴더 안에 생성 하고 싶으면<br>
dok html -y -f<br>
`-f`가 있으면 폴더를 생성하여 만든다는 뜻이다.<br>
<hr>
`dok init`를 입력하면 도크 양식이 뜨는데 npm 같은 거에서는 npm init 같 은 것 이 다<br>
`name : `
<br>`Link : ` (//참고로 github링크만 가능)<br>
`ver : ` (버전)<br>
`by : ` (제작자)<br>
이렇게 양식이 적용됬다.
인제 개발자 issues에 요청을 해주면
보는 즉시 개발자가 올려준다.
그럼 실제로 한 번 올려보자
<pre><code>
Dok 콘솔
[C:~/myconsole] - $ dok init
name : zikijs
Link : https://github.com/boatio/boat.js
by : boatonboat

zikijs|https://github.com/boatio/boat.js/archive/master.zip|1.0|boatonboat   //<<이것을 복사
[C:~/myconsole] - $
</code></pre>
이렇게 복사해주어서 issuge에 올려주면 자동으로 추가된다 그럼 다운을 해보자
만약 개발자가 올렸다고 댓글을 달아주면
<pre><code>
Dok 콘솔
[C:~/myconsole] - $ dok install zikijs
Get... Data Json
Find Moduel..
download  Package..
100% [............................................................] 4581 / 4581
zikijs @ 1.0
Made by  boatonboat
</code></pre>
이렇게 뜬다
한 번 올려보자 
